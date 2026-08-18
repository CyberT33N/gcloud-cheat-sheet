# Storage

## Buckets

### Create
```shell
$bucket = "test-software-dep-evidence-archive" ; gcloud storage buckets create "gs://$bucket" --project=test-software-dep-evidence --location=europe-west3 --uniform-bucket-level-access --public-access-prevention 2>&1 
```

---

### Describe
```shell
$bucket = "test-software-dep-evidence-archive" ; gcloud storage buckets describe "gs://$bucket" --format="value(name,location,uniformBucketLevelAccess.enabled,publicAccessPrevention)" 2>&1
```