# pam grants describe

Show details of a Privileged Access Manager (PAM) grant.

## Usage

```shell
gcloud pam grants describe <GRANT_NAME> --entitlement=<ENTITLEMENT_ID> --project=<PROJECT_ID> --location=global
```

## Architectural explanation

The describe call is the read-back of a grant: it carries the state machine (`APPROVAL_AWAITED`, `SCHEDULED`, `ACTIVE`, `REVOKED`, and the other terminal forms), the full timeline of events with actors, reasons, and timestamps (`requested`, `approved`, `scheduled`, `activated`, `revoked`), the requester, the requested duration, and the privileged-access content. After a revocation it additionally carries the audit trail of the access window (`auditTrail.accessGrantTime` and `auditTrail.accessRemoveTime`) — the exact interval in which the elevated capability existed. This is the evidence surface of every activation and every drill. The caller needs `privilegedaccessmanager.grants.get` on the resource (for example via [`roles/privilegedaccessmanager.admin`](../../../../iam/roles/predefined/privilegedaccessmanager/admin/overview.md)).

## Verified example

```powershell
gcloud pam grants describe "projects/test-software-dep-control/locations/global/entitlements/dep-break-glass-recovery-admin/grants/<GRANT_ID>" --entitlement=dep-break-glass-recovery-admin --project=test-software-dep-control --location=global
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live grant through its full lifecycle: the answer carried `state: REVOKED` with the complete timeline (requested by the impersonated service account, approved with reason, activated, revoked with reason) and the audit trail bounding the elevated-access window to the exact grant and removal times.
