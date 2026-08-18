# Logging

## Sinks

### list

```shell
gcloud logging sinks list --project=test-software-dep-control 2>&1 
```

---

### create

#### audit-to-evidence

Multiple:
```shell
$bucket = "test-software-dep-evidence-archive" ; foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { Write-Output "== $p" ; gcloud logging sinks create audit-to-evidence "storage.googleapis.com/$bucket" --project=$p --log-filter='logName:"cloudaudit.googleapis.com"' --quiet 2>&1 | Select-Object -Last 2
```


---

### describe

#### audit-to-evidence

Multiple:
```shell
$bucket = "test-software-dep-evidence-archive" ; foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { Write-Output "== $p"; $w = (gcloud logging sinks describe audit-to-evidence --project=$p --format="value(writerIdentity)") ; Write-Output "writer: $w" ; gcloud storage buckets add-iam-policy-binding "gs://$bucket" --member=$w --role=roles/storage.objectCreator --format=none 2>&1 | Select-Object -Last 1 ; Write-Output "bind exit=$LASTEXITCODE" }
```
