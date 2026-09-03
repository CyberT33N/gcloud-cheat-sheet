# logging read

Read log entries of a project through a filter.

## Usage

```shell
gcloud logging read "<FILTER>" --project=<PROJECT_ID> --limit=<N> --freshness=<DURATION> --format=json
```

## Architectural explanation

- The filter speaks the logging query language; a Cloud Run job's workload logs carry `resource.type="cloud_run_job"` and `resource.labels.job_name="<JOB_NAME>"`, and the audit log of a project matches `logName:"cloudaudit.googleapis.com"`.
- A VPC Service Controls denial is visible in the audit entry: `protoPayload.status.code=7` with the message "Request is prohibited by organization's policy" and a `vpcServiceControlsUniqueIdentifier`. The `protoPayload.metadata` carries the violation kind (`ingressViolations` or `egressViolations`), the target resource, the denied permission and the violation reason (for example `NO_MATCHING_ACCESS_LEVEL`). This distinguishes a perimeter denial from a plain IAM denial, which carries no VPC-SC marker.
- `--freshness` bounds the read window (for example `1h`), `--limit` the entry count; the JSON form composes with `ConvertFrom-Json` in PowerShell for field-level proof.
- The read requires `logging.logEntries.list` on the project (for example via a time-boxed `roles/logging.viewer` grant); in a hardened project without standing user roles the call fails closed until such a grant exists.

## Verified example (workload failure logs of one job)

```shell
gcloud logging read "resource.type=cloud_run_job AND resource.labels.job_name=dep-intake-fetch" --project=test-software-dep-intake --limit=50 --freshness=1h --format=json
```

## Verified example (perimeter denials of one identity)

```shell
gcloud logging read "logName:cloudaudit.googleapis.com AND protoPayload.status.code=7 AND protoPayload.authenticationInfo.principalEmail=<SERVICE_ACCOUNT_EMAIL>" --project=test-software-dep-intake --limit=5 --freshness=2h --format=json
```
