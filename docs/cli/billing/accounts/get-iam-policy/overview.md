# billing accounts get-iam-policy

Read the IAM policy of a Cloud Billing account.

## Usage

```shell
gcloud billing accounts get-iam-policy <BILLING_ACCOUNT_ID> --format=json
```

## Architectural explanation

The billing account IAM policy is the authorization surface of the financial plane. The JSON form composes with `ConvertFrom-Json` for exact member/role assertions — filtering `bindings` on a member proves which billing roles that member holds. The read itself needs a billing-account role (for example [`roles/billing.user`](../../../../iam/roles/predefined/billing/user/overview.md), which carries [`billing.accounts.getIamPolicy`](../../../../iam/permissions/billing/accounts/overview.md#billingaccountsgetiampolicy)): without one the call fails closed with permission denied — an absent proof is itself evidence that the delegation has not happened.

## Verified example

```powershell
$pol = gcloud billing accounts get-iam-policy <BILLING_ACCOUNT_ID> --format=json | ConvertFrom-Json
$pol.bindings | Where-Object { $_.members -contains 'user:admin@test.software' } | ForEach-Object { $_.role }
```

Proven result: `roles/billing.user` (verified after the billing-plane delegation of the foundation state-home key birth).
