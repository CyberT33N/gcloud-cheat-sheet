# run jobs executions describe

Read the status of one job execution.

## Usage

```shell
gcloud run jobs executions describe <EXECUTION_NAME> --project=<PROJECT_ID> --region=<REGION> --format=json
```

## Architectural explanation

The v2 execution resource wraps its status fields under `status` — `status.completionTime`, `status.succeededCount`, `status.failedCount`, `status.logUri` — plus `status.conditions`, which carries the terminal condition (for example `reason: NonZeroExitCode` with the container exit message). The fail-closed success assertion of a lane is: `.status.completionTime != null and ((.status.succeededCount // 0) >= 1) and ((.status.failedCount // 0) == 0)`. The `status.logUri` is the audit pointer to the workload logs; the execution name is the answer of [execute](../execute/overview.md) with `--format="value(name)"`.

## Verified example

```shell
gcloud run jobs executions describe <EXECUTION_NAME> --project=test-software-dep-intake --region=europe-west3 --format=json
```

