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
- The read requires `logging.logEntries.list` on the project (for example via a time-boxed [`roles/logging.viewer`](../../../iam/roles/predefined/logging/viewer/overview.md) grant); in a hardened project without standing user roles the call fails closed until such a grant exists.

## Verified example (workload failure logs of one job)

```shell
gcloud logging read "resource.type=cloud_run_job AND resource.labels.job_name=dep-intake-fetch" --project=test-software-dep-intake --limit=50 --freshness=1h --format=json
```

## Verified example (perimeter denials of one identity)

```shell
gcloud logging read "logName:cloudaudit.googleapis.com AND protoPayload.status.code=7 AND protoPayload.authenticationInfo.principalEmail=<SERVICE_ACCOUNT_EMAIL>" --project=test-software-dep-intake --limit=5 --freshness=2h --format=json
```

## Troubleshooting: timestamp-literal filters fail at the Windows PowerShell boundary

A filter carrying a timestamp literal (for example `timestamp>="2026-09-24T00:00:00Z"`) passed directly from PowerShell fails with `ERROR: (gcloud.logging.read) INVALID_ARGUMENT: Unparseable filter: syntax error at line 1, column <n>, token ':'` — the value-carrying argument is mangled at the native-command boundary before it reaches the API. Two proven forms (verified with Google Cloud SDK 580.0.0 on windows_amd64):

- Use `--freshness=<duration>` instead of a timestamp literal and keep the default `--order=desc` (the help surface binds: freshness works only with DESC ordering and with filters that carry no timestamp); reverse client-side for a chronological view.
- Or carry the exact filter through a `cmd /c` subshell with `\"` escaping:

```powershell
cmd /c 'gcloud logging read "logName:\"cloudaudit.googleapis.com\" AND protoPayload.methodName:\"SetIamPolicy\" AND timestamp>=\"<RFC3339_FROM>\" AND timestamp<=\"<RFC3339_TO>\"" --project=<PROJECT_ID> --limit=<N> --order=asc --format=json'
```

## Deep dive: IAM-mutation forensics over the admin activity log

Verified pattern for "who changed the IAM policy" questions: read the project's admin activity audit log with `logName:"cloudaudit.googleapis.com" AND protoPayload.methodName:"SetIamPolicy"` and project each entry to `timestamp`, `protoPayload.authenticationInfo.principalEmail`, and the role set inside `protoPayload.request.policy.bindings`. Two verified lessons: (1) the project log also carries resource-level `SetIamPolicy` entries of other services in the project (for example `cloudkms.googleapis.com` key policies) — distinguish on `protoPayload.serviceName` before comparing policy contents, or a key-level entry reads as an empty project policy; (2) a removal that reports `Policy binding with the specified principal, role, and condition not found!` means the binding was already absent — the audit timeline then shows which earlier `SetIamPolicy` call removed it and under which identity.
