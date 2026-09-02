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


---

### add-iam-policy-binding

Multiple
```shell
$bucket = "test-software-dep-evidence-archive" ; foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { Write-Output "== $p"; $w = (gcloud logging sinks describe audit-to-evidence --project=$p --format="value(writerIdentity)") ; Write-Output "writer: $w" ; if ($w) { gcloud storage buckets add-iam-policy-binding "gs://$bucket" --member=$w --role=roles/storage.objectCreator --format=none 2>&1 | Select-Object -Last 1 ; Write-Output "bind exit=$LASTEXITCODE" } }
```


---

### get-iam-polic


```shell
gcloud storage buckets get-iam-policy gs://test-software-dep-evidence-archive --flatten="bindings[].members" --filter="bindings.role=roles/storage.objectCreator" --format="value(bindings.members)"
```