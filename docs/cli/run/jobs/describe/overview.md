# run jobs describe

Read the full specification and the live status of one Cloud Run job.

## Usage

```shell
gcloud run jobs describe <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --format=json
```

## Architectural explanation

Returns the complete job resource: the container image, the attached service account, the environment bindings, the labels and under `status.conditions` the readiness evaluation. The `Ready` condition is the platform-side proof that the job is executable (including the image access validation). In PowerShell the JSON form composes with `ConvertFrom-Json` for property-level assertions; the `lastTransitionTime` of the condition proves whether the evaluation is current or stale.

## Verified example

```shell
gcloud run jobs describe dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --format="json(status.conditions)"
```

A healthy job reports `"status": "True"` on the `Ready` condition with a current `lastTransitionTime`.
