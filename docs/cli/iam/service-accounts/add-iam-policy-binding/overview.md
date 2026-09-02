# add-iam-policy-binding

```shell
gcloud iam service-accounts add-iam-policy-binding "dep-revocation-controller@test-software-dep-control.iam.gserviceaccount.com" --project=test-software-dep-control --role="roles/iam.workloadIdentityUser" --member="principalSet://iam.googleapis.com/projects/xxxxxxxxxxxx/locations/global/workloadIdentityPools/dep-control-github/attribute.environment/dep-revocation" --format=none
```
