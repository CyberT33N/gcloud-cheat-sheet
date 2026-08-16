# Organizations 

## List
```shell
gcloud organizations list
```

### get-iam-policy
```shell
gcloud organizations get-iam-policy xxxxxxxxxxxx --format="yaml(bindings)"
```


### remove-iam-policy-binding
```shell
gcloud organizations remove-iam-policy-binding xxxxxxxxxxxxx --member="domain:test.software" --role="roles/billing.creator" --format=none
```