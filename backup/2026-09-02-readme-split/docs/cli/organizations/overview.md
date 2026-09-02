# Organizations 

## List
```shell
gcloud organizations list
```

### add-iam-policy-binding
```shell
gcloud organizations add-iam-policy-binding xxxxxxxxxx --member="user:admin@test.software" --role="roles/orgpolicy.policyAdmin" --format=none
```


### get-iam-policy
```shell
gcloud organizations get-iam-policy xxxxxxxxxxxx --format="yaml(bindings)"
```


### remove-iam-policy-binding
```shell
gcloud organizations remove-iam-policy-binding xxxxxxxxxxxxx --member="domain:test.software" --role="roles/billing.creator" --format=none
```