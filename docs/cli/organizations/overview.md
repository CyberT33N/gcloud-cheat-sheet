# Organizations 

## List
```shell
gcloud organizations list
```

### add-iam-policy-binding
```shell
gcloud organizations add-iam-policy-binding xxxxxxxxxx --member="user:admin@test.software" --role="roles/orgpolicy.policyAdmin" --format=none
```

Role reference: [`roles/orgpolicy.policyAdmin`](../../iam/roles/predefined/orgpolicy/policyAdmin/overview.md) — the IAM roles area documents the full permission set of this role.


### get-iam-policy
```shell
gcloud organizations get-iam-policy xxxxxxxxxxxx --format="yaml(bindings)"
```


### remove-iam-policy-binding
```shell
gcloud organizations remove-iam-policy-binding xxxxxxxxxxxxx --member="domain:test.software" --role="roles/billing.creator" --format=none
```

Role reference: [`roles/billing.creator`](../../iam/roles/predefined/billing/creator/overview.md) — the IAM roles area documents the full permission set of this role.