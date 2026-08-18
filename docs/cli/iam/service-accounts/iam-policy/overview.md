# IAM

## Service Accounts

### IAM

#### Policy

##### Get
```shell
gcloud iam service-accounts get-iam-policy gba-builder-promoter@cybertest-go-builder-authority.iam.gserviceaccount.com --project=test-go-builder-authority --format="yaml(bindings)"
```


##### Add
```shell
gcloud iam service-accounts add-iam-policy-binding "dep-revocation-controller@test-software-dep-control.iam.gserviceaccount.com" --project=test-software-dep-control --role="roles/iam.workloadIdentityUser" --member="principalSet://iam.googleapis.com/projects/xxxxxxxxxxxx/locations/global/workloadIdentityPools/dep-control-github/attribute.environment/dep-revocation" --format=none
```