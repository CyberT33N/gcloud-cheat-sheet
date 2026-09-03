# run jobs execute

Execute one Cloud Run job, optionally with execution-parameter overrides.

## Usage

```shell
gcloud run jobs execute <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --update-env-vars="^;^<KEY>=<VALUE>;..." --wait --format="value(name)"
```

## Architectural explanation

- `--update-env-vars` passes per-execution inputs as template overrides; the `^;^` prefix switches the key/value delimiter to `;`, so values may contain commas. This makes the call an override execution: it requires `run.jobs.runWithOverrides` on the job, not only `run.jobs.run`. The proven least-privilege role pair for a trigger identity is `roles/run.jobsExecutorWithOverrides` (carrying `run.jobs.run`, `run.jobs.runWithOverrides` and `run.executions.cancel`) plus `roles/run.viewer` for the status read-back — `roles/run.invoker` alone fails closed with `PERMISSION_DENIED: Permission 'run.jobs.runWithOverrides' denied`.
- `--wait` is mandatory for the status proof: without it the command returns at execution start, not at its outcome.
- `--format="value(name)"` reduces the answer to the execution resource name for the read-back over [executions describe](../executions/describe/overview.md).
- The execution runs as the job's attached service account; the caller identity never enters the data plane.

## Verified example

```shell
gcloud run jobs execute dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --update-env-vars="^;^DEPENDENCY_AUTHORITY_MODULE=<MODULE>;DEPENDENCY_AUTHORITY_VERSION=<VERSION>" --wait --format="value(name)"
```

## Troubleshooting

**`PERMISSION_DENIED` on `run.jobs.runWithOverrides`.** The trigger identity holds `roles/run.invoker` only. Swap the binding to `roles/run.jobsExecutorWithOverrides` (add the new role first, then remove the old one) and retry; see [add-iam-policy-binding](../add-iam-policy-binding/overview.md) and [remove-iam-policy-binding](../remove-iam-policy-binding/overview.md).

**The execution starts but fails.** The invoke succeeded; the failure is inside the workload. Read the execution status over [executions describe](../executions/describe/overview.md) and the workload logs over `gcloud logging read` (see the logging read document).

