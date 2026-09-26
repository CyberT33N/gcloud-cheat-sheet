# pam entitlements describe

Show details of a Privileged Access Manager (PAM) entitlement.

## Usage

```shell
gcloud pam entitlements describe <ENTITLEMENT_ID> --project=<PROJECT_ID> --location=global
```

## Architectural explanation

The describe call is the read-back of an entitlement: it proves the live form against the declared form — the role set of the privileged access, the `maxRequestDuration`, the approval workflow (the approver principals, the approvals needed, whether approver justification is required), the eligible requester principals, and the state. The state `AVAILABLE` means the entitlement is ready for grant requests; newly created entitlements can take a few minutes to propagate before they become usable. The caller needs `privilegedaccessmanager.entitlements.get` on the resource (for example via [`roles/privilegedaccessmanager.admin`](../../../../iam/roles/predefined/privilegedaccessmanager/admin/overview.md)).

## Verified example

```powershell
gcloud pam entitlements describe dep-break-glass-recovery-admin --project=test-software-dep-control --location=global
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live entitlement: the answer carried the full form — the thirteen project-grantable role bindings on the project resource, `maxRequestDuration: 7200s`, the manual approval workflow with `requireApproverJustification: true` and one approval step, the single eligible service-account principal, and `state: AVAILABLE`.
