# pam grants approve

Approve a Privileged Access Manager (PAM) grant with a reason.

## Usage

```shell
gcloud pam grants approve <GRANT_NAME> --entitlement=<ENTITLEMENT_ID> --project=<PROJECT_ID> --location=global --reason=<REASON>
```

## Architectural explanation

The approval acts on a grant in the `APPROVAL_AWAITED` state and cannot be undone. The approval authority comes from the entitlement's approval-workflow approver list — the caller must be a listed approver of the entitlement; no IAM permission carries the approval capability (the predefined roles carry only grant read surfaces such as `privilegedaccessmanager.grants.get`/`list`). The reason is recorded on the grant's timeline; when the entitlement sets `requireApproverJustification`, the reason is mandatory. After the approval the grant is scheduled and then activated: Privileged Access Manager itself creates the time-bound role bindings of the entitlement on the target resource — never the approver and never the requester.

## Verified example

```powershell
gcloud pam grants approve "projects/test-software-dep-control/locations/global/entitlements/dep-break-glass-recovery-admin/grants/<GRANT_ID>" --entitlement=dep-break-glass-recovery-admin --project=test-software-dep-control --location=global --reason="Drill approval: reviewed operational event"
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live grant: the approval moved the grant to `SCHEDULED` with the timeline carrying the `approved` event (the approver actor and the recorded reason) followed by the `scheduled` event with the activation time; the grant then reached `ACTIVE` and the requester held the elevated roles for the granted window.
