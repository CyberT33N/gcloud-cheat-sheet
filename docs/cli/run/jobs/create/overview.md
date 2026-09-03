# run jobs create

Create a Cloud Run job: the one-shot execution form of a containerized workload.

## Usage

```shell
gcloud run jobs create <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --image=<IMAGE_DIGEST_REF> --service-account=<SERVICE_ACCOUNT_EMAIL> --labels="<KEY>=<VALUE>,..." --set-env-vars="^;^<KEY>=<VALUE>;..."
```

## Architectural explanation

- `--image` binds the container image; the governed form is the full immutable `@sha256:` digest reference of a release-class registry, never a tag.
- `--service-account` attaches the execution identity the workload runs as; the caller needs `iam.serviceAccounts.actAs` on that identity (for example via a resource-scoped `roles/iam.serviceAccountUser` binding) plus `run.jobs.create` on the project (via `roles/run.admin`).
- `--labels` carries the governance classification of the job.
- `--set-env-vars` with the `^;^` prefix switches the key/value delimiter to `;`, so values may contain commas and other list metacharacters. Static configuration belongs here; execution-time inputs belong to `gcloud run jobs execute --update-env-vars`.
- The job is created in the project that owns it; the image may live in another project (see the troubleshooting entry).

## Verified example

```shell
gcloud run jobs create dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --image=europe-west3-docker.pkg.dev/test-software-dep-control/release-controller-images/dependency-intake-controller@sha256:<DIGEST> --service-account=dep-intake-fetcher@test-software-dep-intake.iam.gserviceaccount.com --labels="boundary=dependency-authority,zone=intake" --set-env-vars="^;^DEPENDENCY_AUTHORITY_ZONE=intake;DEPENDENCY_AUTHORITY_ECOSYSTEM=go;DEPENDENCY_AUTHORITY_ARTIFACT_API=https://artifactregistry.googleapis.com"
```

## Troubleshooting

**`ContainerPermissionDenied` on a cross-project image.** The image pull at creation and execution time is performed by the Cloud Run Service Agent of the job's project (`service-<PROJECT_NUMBER>@serverless-robot-prod.iam.gserviceaccount.com`), not by the job's service account. When the image lives in another project, that agent needs `roles/artifactregistry.reader` on the source repository:

```shell
gcloud artifacts repositories add-iam-policy-binding <REPOSITORY_NAME> --project=<IMAGE_PROJECT_ID> --location=<REGION> --member="serviceAccount:service-<JOB_PROJECT_NUMBER>@serverless-robot-prod.iam.gserviceaccount.com" --role="roles/artifactregistry.reader"
```

The job resource itself is still created; its `Ready` condition stays `False` until the grant exists. The condition is not re-evaluated continuously — force re-validation with a no-op update (see [update](../update/overview.md)). The service agent identity is created when the Cloud Run API is enabled on the project; a freshly enabled API may need a few minutes to propagate.
