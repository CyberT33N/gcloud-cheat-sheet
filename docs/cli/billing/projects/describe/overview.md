# billing projects describe

Show the billing information of one project.

## Usage

```shell
gcloud billing projects describe <PROJECT_ID> --format="value(projectId,billingAccountName,billingEnabled)"
```

## Architectural explanation

Prints the billing state of the project: the linked account reference and `billingEnabled`. This is the independent read-back half of every billing link — the link is proven by the described state, never by the mutation echo. A project without a link reports `billingEnabled: false` with an empty account reference.

## Verified example

```shell
gcloud billing projects describe test-software-org-anchor --format="value(projectId,billingAccountName,billingEnabled)"
```

Proven result after the link: `test-software-org-anchor`, `billingAccounts/<BILLING_ACCOUNT_ID>`, `True` (verified during the foundation state-home key birth).
