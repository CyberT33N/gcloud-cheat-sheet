# add-iam-policy-binding

## Workload Identity federation binding (principalSet member)

```shell
gcloud iam service-accounts add-iam-policy-binding "dep-revocation-controller@test-software-dep-control.iam.gserviceaccount.com" --project=test-software-dep-control --role="roles/iam.workloadIdentityUser" --member="principalSet://iam.googleapis.com/projects/xxxxxxxxxxxx/locations/global/workloadIdentityPools/dep-control-github/attribute.environment/dep-revocation" --format=none
```

## User member (time-boxed administration)

```shell
gcloud iam service-accounts add-iam-policy-binding dep-intake-fetcher@test-software-dep-intake.iam.gserviceaccount.com --project=test-software-dep-intake --role="roles/iam.serviceAccountUser" --member="user:admin@test.software"
```

## Architectural explanation

The binding is service-account-scoped: the member receives the role on exactly this service account. `roles/iam.serviceAccountUser` carries `iam.serviceAccounts.actAs` — the permission to attach the identity to a resource (for example a Cloud Run job). The caller needs `iam.serviceAccounts.setIamPolicy` on the service account (for example via project-level `roles/iam.serviceAccountAdmin`). Every grant is proven by the read-back over [get-iam-policy](../get-iam-policy/overview.md) and removed after the phase over [remove-iam-policy-binding](../remove-iam-policy-binding/overview.md).
