# billing projects link

Link a project with a Cloud Billing account.

## Usage

```shell
gcloud billing projects link <PROJECT_ID> --billing-account=<BILLING_ACCOUNT_ID>
```

## Architectural explanation

Sets or updates the billing account of a project; billing is enabled exactly when the project is linked to a valid, active account. The call needs two permissions on two different planes: `billing.resourceAssociations.create` on the billing account (for example via the one-directional [`roles/billing.user`](../../../../iam/roles/predefined/billing/user/overview.md) — it links and never unlinks) and `resourcemanager.projects.createBillingAssignment` on the project (via [`roles/billing.projectManager`](../../../../iam/roles/predefined/billing/projectManager/overview.md), which carries exactly the create/delete billing-assignment pair). The read-back half is [describe](../describe/overview.md): `billingEnabled: true` with the exact account reference.

## Verified example

```shell
gcloud billing projects link test-software-org-anchor --billing-account=<BILLING_ACCOUNT_ID>
```

Proven result: the project reports `billingEnabled: true` with `billingAccounts/<BILLING_ACCOUNT_ID>` on the describe read-back (verified during the foundation state-home key birth).
