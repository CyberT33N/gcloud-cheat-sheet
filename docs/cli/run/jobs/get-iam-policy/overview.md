# run jobs get-iam-policy

Read the IAM policy of one Cloud Run job.

## Usage

```shell
gcloud run jobs get-iam-policy <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --format=json
```

## Architectural explanation

The job-level IAM policy is the resource-scoped authorization surface of the job: who may invoke it and who may read its executions. Reading it after every binding change is the independent proof that the intended member/role pair — and nothing else — is bound. In PowerShell the JSON form composes with `ConvertFrom-Json` for exact member assertions; an absent `bindings` property proves the empty policy.

## Verified example

```shell
gcloud run jobs get-iam-policy dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --format=json
```
