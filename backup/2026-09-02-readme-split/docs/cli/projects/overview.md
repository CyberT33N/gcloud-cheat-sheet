# Projects


## Create
docs\cli\projects\create.md

---

## Move
docs\cli\projects\move.md


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


## get-iam-policy-binding


```shell
gcloud projects get-iam-policy test-software-dep-intake --flatten=bindings[].members --filter=bindings.members:dep-intake-fetcher --format="yaml(bindings.role,bindings.members)"
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