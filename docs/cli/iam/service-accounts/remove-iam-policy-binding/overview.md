# remove-iam-policy-binding

Remove one member/role binding from the IAM policy of a service account.

## Usage

```shell
gcloud iam service-accounts remove-iam-policy-binding <SERVICE_ACCOUNT_EMAIL> --project=<PROJECT_ID> --role="<ROLE>" --member="<MEMBER>"
```

## Architectural explanation

The removal targets exactly the member form that was granted; the read-back over [get-iam-policy](../get-iam-policy/overview.md) proves the policy afterwards. Ordering rule for time-boxed (just-in-time) administration: the identity performing service-account-level IAM changes needs `iam.serviceAccounts.setIamPolicy` (for example via project-level `roles/iam.serviceAccountAdmin`). Remove service-account-level bindings first and the project-level administration role last — removing the administration role first strands the service-account-level bindings behind `PERMISSION_DENIED`.

## Verified example

```shell
gcloud iam service-accounts remove-iam-policy-binding dep-intake-fetcher@test-software-dep-intake.iam.gserviceaccount.com --project=test-software-dep-intake --role="roles/iam.serviceAccountUser" --member="user:admin@test.software"
```
