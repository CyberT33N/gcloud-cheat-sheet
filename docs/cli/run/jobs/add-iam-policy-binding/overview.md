# run jobs add-iam-policy-binding

Bind a member to a role on exactly one Cloud Run job.

## Usage

```shell
gcloud run jobs add-iam-policy-binding <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --member="serviceAccount:<SERVICE_ACCOUNT_EMAIL>" --role="<ROLE>"
```

## Architectural explanation

The binding is resource-scoped: the member receives the role on this job and nowhere else — the least-privilege form for invoke-only trigger identities. The proven role contents (read first via `gcloud iam roles describe`): `roles/run.invoker` carries `run.jobs.run` (the plain invoke permission); `roles/run.jobsExecutorWithOverrides` carries `run.jobs.run`, `run.jobs.runWithOverrides` and `run.executions.cancel` — the override-execution form, required whenever the invocation passes execution-parameter overrides such as `--update-env-vars`; `roles/run.viewer` carries `run.executions.get` and `run.executions.list` (the execution status read-back), and the remaining viewer permissions do not apply to a job resource. For a lane that passes operation inputs as overrides the proven pair is `roles/run.jobsExecutorWithOverrides` plus `roles/run.viewer` — `roles/run.invoker` alone fails closed with `PERMISSION_DENIED` on `run.jobs.runWithOverrides`.

## Verified example

```shell
gcloud run jobs add-iam-policy-binding dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --member="serviceAccount:dep-intake-fetch-trigger@test-software-dep-intake.iam.gserviceaccount.com" --role="roles/run.jobsExecutorWithOverrides"
gcloud run jobs add-iam-policy-binding dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --member="serviceAccount:dep-intake-fetch-trigger@test-software-dep-intake.iam.gserviceaccount.com" --role="roles/run.viewer"
```

The read-back runs over [get-iam-policy](../get-iam-policy/overview.md).
