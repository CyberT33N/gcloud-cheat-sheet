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
