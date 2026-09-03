# run jobs executions describe

Read the status of one job execution.

## Usage

```shell
gcloud run jobs executions describe <EXECUTION_NAME> --project=<PROJECT_ID> --region=<REGION> --format=json
```

## Architectural explanation

The v2 execution resource carries its status fields flat on the top level — `completionTime`, `succeededCount`, `failedCount`, `logUri` — with no `.status` wrapper. The fail-closed success assertion of a lane is: `.completionTime != null and ((.succeededCount // 0) >= 1) and ((.failedCount // 0) == 0)`. The `logUri` is the audit pointer to the workload logs; the execution name is the answer of [execute](../execute/overview.md) with `--format="value(name)"`.

## Verified example

```shell
gcloud run jobs executions describe <EXECUTION_NAME> --project=test-software-dep-intake --region=europe-west3 --format=json
```

