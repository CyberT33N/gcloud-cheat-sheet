# logging write

Write one log entry.

## Usage

```shell
gcloud logging write <LOG_NAME> "<MESSAGE>" --project=<PROJECT_ID>
```

## Architectural explanation

The write creates a log entry (the destination log is created if absent). In a governed, read-only context the write is the mutation-refusal probe: an identity holding only read roles (for example [`roles/logging.viewer`](../../../iam/roles/predefined/logging/viewer/overview.md), which carries `logging.logEntries.list` but not `logging.logEntries.create`) must fail closed with `IAM_PERMISSION_DENIED` naming `logging.logEntries.create`. A successful write against such an identity is a governance finding, not a success.

## Verified example (mutation-refusal probe)

```shell
gcloud logging write forensics-readonly-probe "forensics read-only mutation probe" --project=test-software-dep-intake
```
