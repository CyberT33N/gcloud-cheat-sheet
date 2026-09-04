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
