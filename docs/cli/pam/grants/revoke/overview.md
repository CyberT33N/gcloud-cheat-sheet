# pam grants revoke

Revoke a Privileged Access Manager (PAM) grant with a reason.

## Usage

```shell
gcloud pam grants revoke <GRANT_NAME> --entitlement=<ENTITLEMENT_ID> --project=<PROJECT_ID> --location=global --reason=<REASON>
```

## Architectural explanation

The revocation is the early closure of an active grant: Privileged Access Manager removes the time-bound role bindings it created for the grant. The removal follows standard access-change propagation — the elevated capability disappears after the propagation window, not instantly. The proven form: immediately after the revocation the impersonated elevated read still succeeded; after a short propagation window (about 90 seconds) the same read failed closed with the permission denied. Always prove the hardened end state by re-running the previously elevated call after the propagation window, never by the revocation echo alone. The caller needs `privilegedaccessmanager.grants.revoke` on the resource (for example via [`roles/privilegedaccessmanager.admin`](../../../../iam/roles/predefined/privilegedaccessmanager/admin/overview.md)).

## Verified example

```powershell
gcloud pam grants revoke "projects/test-software-dep-control/locations/global/entitlements/dep-break-glass-recovery-admin/grants/<GRANT_ID>" --entitlement=dep-break-glass-recovery-admin --project=test-software-dep-control --location=global --reason="Drill complete: early revocation closes the reviewed operational event"
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live grant: the revocation completed with `state: REVOKED`, the timeline carrying the `revoked` event with the actor and the recorded reason, and the audit trail bounding the access window; the elevated read of a zone resource failed closed after the propagation window.
