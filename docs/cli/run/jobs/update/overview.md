# run jobs update

Update a Cloud Run job; the no-op form forces re-validation.

## Usage

```shell
gcloud run jobs update <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --update-labels="<KEY>=<VALUE>"
```

## Architectural explanation

Cloud Run evaluates the job's `Ready` condition at generation changes, not continuously. After fixing a cause outside the job — for example granting the Cloud Run Service Agent read access to a cross-project image — the stale denial remains visible until a new generation forces re-evaluation. Re-applying an already-present label value is the minimal no-op mutation that bumps the generation without changing the intended state.

## Verified example

```shell
gcloud run jobs update dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --update-labels="boundary=dependency-authority"
```

Followed by the read-back over [describe](../describe/overview.md), the `Ready` condition flips to `"True"` once the external cause is resolved.

## Direct VPC egress form (network attachment)

```shell
gcloud run jobs update <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --network=projects/<PROJECT_ID>/global/networks/<NETWORK> --subnet=projects/<PROJECT_ID>/regions/<REGION>/subnetworks/<SUBNET> --vpc-egress=all-traffic
```

Architectural explanation: the Direct VPC egress form attaches the job to a VPC without a connector; `--vpc-egress=all-traffic` routes ALL outbound traffic through the attachment (the deprecated alias `all` exists — use `all-traffic`). The subnet must be /26 or larger. The update re-validates `iam.serviceAccounts.actAs` on the attached service account, so the caller needs that grant (for example a time-boxed SA-scoped `roles/iam.serviceAccountUser` binding) even when the service account itself does not change. The read-back runs over [describe](../describe/overview.md): in the gcloud v1 presentation the attachment surfaces as the template annotations `run.googleapis.com/network-interfaces` and `run.googleapis.com/vpc-access-egress`, not as a spec field.

## Image and environment update form

```shell
gcloud run jobs update <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --image=<REGION>-docker.pkg.dev/<PROJECT_ID>/<REPOSITORY>/<IMAGE>@sha256:<DIGEST> --update-env-vars="^;^<KEY>=<VALUE>;<KEY>=<VALUE>"
```

Architectural explanation: the `--image` form re-binds the job to a new immutable digest reference, and `--update-env-vars` merges the named variables into the execution template (the `^;^` prefix sets `;` as the delimiter, so values may carry commas and other separator-sensitive content). The update re-validates `iam.serviceAccounts.actAs` on the attached service account even when the identity itself does not change: a caller without the actAs grant is rejected fail-closed with `PERMISSION_DENIED: Permission 'iam.serviceaccounts.actAs' denied`, and the rejected update mutates nothing (proven by the describe read-back of the unchanged job). The read-back runs over [describe](../describe/overview.md): the new image and the merged env bindings surface under `spec.template.spec.template.spec.containers[0]`, and the `Ready` condition re-evaluates at the new generation.

The same generation change also re-validates image access under the caller's identity: the caller must hold `artifactregistry.repositories.downloadArtifacts` on the image's repository even when the image reference itself does not change — a caller without it is rejected fail-closed with `PERMISSION_DENIED: Permission 'artifactregistry.repositories.downloadArtifacts' denied` on the repository, and the rejected update mutates nothing. The proven least-privilege window form is two-layered: the management shell `roles/artifactregistry.admin` (project-scoped, carrying the registry `getIamPolicy`/`setIamPolicy`) exists only around the registry IAM-administration steps, the data-plane read runs under `roles/artifactregistry.reader` repository-scoped on the image repository (carrying `downloadArtifacts`), and the shell is absent while the update runs. After every IAM change allow a short propagation window (about 60–90 seconds) and pre-verify with a simpler permission proof before the dependent operation; every grant is removed afterwards and the hardened end state is proven by read-back.
