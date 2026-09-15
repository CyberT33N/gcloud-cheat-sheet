# billing accounts add-iam-policy-binding

Add an IAM policy binding to a Cloud Billing account.

## Usage

```shell
gcloud billing accounts add-iam-policy-binding <BILLING_ACCOUNT_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The grant surface of the billing account — the financial plane of the organization. The canonical delegation form for the platform operator is exactly [`roles/billing.user`](../../../../iam/roles/predefined/billing/user/overview.md): it carries `billing.resourceAssociations.create` (the one-directional link capability — never delete, never update) plus the read surface (`billing.accounts.get/list/getIamPolicy`) that the verification lane needs. Never [`roles/billing.admin`](../../../../iam/roles/predefined/billing/admin/overview.md) (full financial administration including unlink and account close). The grant itself is a root-of-trust act: only an existing billing account administrator can issue it. The read-back half is [get-iam-policy](../get-iam-policy/overview.md).

## Verified example

```shell
gcloud billing accounts add-iam-policy-binding <BILLING_ACCOUNT_ID> --member="user:admin@test.software" --role="roles/billing.user"
```

Proven result: the account policy carries `user:admin@test.software` with [`roles/billing.user`](../../../../iam/roles/predefined/billing/user/overview.md) on the read-back (the delegation was executed through the console surface by the billing account owner; the form here is the verified CLI equivalent).
