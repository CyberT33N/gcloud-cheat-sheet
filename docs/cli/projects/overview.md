# Projects


## Create

### Multiple projects
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== create test-software-dep-$z =="; gcloud projects create "test-software-dep-$z" --name="test-software-dep-$z" --labels="boundary=dependency-authority,zone=$z" --format="value(projectId,lifecycleState)" }
```


---

## Move
1. Run install beta
- docs\cli\components\overview.md

2. Then move:
```shell
gcloud beta projects move test-software-dep-control --folder=xxxxxxxxxxxxxx --quiet 2>&1
```



---

## List
```shell
gcloud projects list
```

## Describe
```shell
gcloud projects describe
```


---

## add-iam-policy-binding

### Multiple
```shell
foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { Write-Output "== $p" ; gcloud projects add-iam-policy-binding $p --member="user:admin@test.software" --role="roles/resourcemanager.projectMover" --format="value(bindings.role)" --flatten="bindings" }
```


## remove-iam-policy-binding
```shell
gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:test@gmail.com" --role="roles/owner" --format=none ; Write-Output "remove-owner exit=$LASTEXITCODE"
```