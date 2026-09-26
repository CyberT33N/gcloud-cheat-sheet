# pam grants create

Create a new Privileged Access Manager (PAM) grant under an entitlement — the request for temporary elevation.

## Usage

```shell
gcloud pam grants create --entitlement=<ENTITLEMENT_ID> --project=<PROJECT_ID> --location=global --requested-duration=<DURATION> --justification=<JUSTIFICATION> --impersonate-service-account=<SERVICE_ACCOUNT_EMAIL>
```

## Architectural explanation

The requester creates a grant against an entitlement; the requested duration never exceeds the entitlement's `max_request_duration` (the platform enforces the time-box), and the justification is recorded on the grant. When the entitlement mandates approval, the new grant lands in the `APPROVAL_AWAITED` state. The requester authority comes from the entitlement's eligible-users list — no IAM permission is required to request; the caller must simply be an eligible principal of the entitlement.

The `--impersonate-service-account` form lets the operator execute the request as the dedicated identity (for example a break-glass recovery identity) instead of their personal account: the caller needs `iam.serviceAccounts.getAccessToken` on that identity, carried by [`roles/iam.serviceAccountTokenCreator`](../../../../iam/roles/predefined/iam/serviceAccountTokenCreator/overview.md). Note the boundary proven by the role-content read: [`roles/iam.serviceAccountUser`](../../../../iam/roles/predefined/iam/serviceAccountUser/overview.md) carries `iam.serviceAccounts.actAs` but not `iam.serviceAccounts.getAccessToken` — it does not cover the permission the impersonation token generation requires, so the token-creator form is the binding one.

## Verified example

```powershell
gcloud pam grants create --entitlement=dep-break-glass-recovery-admin --project=test-software-dep-control --location=global --requested-duration=7200s --justification="Drill: proof of the recovery activation path" --impersonate-service-account=dep-break-glass-recovery@test-software-dep-control.iam.gserviceaccount.com
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live entitlement: the grant was created as `projects/test-software-dep-control/locations/global/entitlements/dep-break-glass-recovery-admin/grants/<GRANT_ID>` with the requesting identity recorded as the impersonated service account, the justification stored, and `state: APPROVAL_AWAITED`.
