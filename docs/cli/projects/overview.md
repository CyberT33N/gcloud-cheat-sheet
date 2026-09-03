# Projects


## Create

- [Create](create.md)

---

## Move

- [Move](move.md)


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

---

## Just-in-time administration lifecycle

The project-level grant is the time-boxed administration form: grant the role, prove it with the read-back, let it propagate, execute the phase, remove the role, prove the removal.

```shell
gcloud projects add-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/run.admin"
gcloud projects get-iam-policy test-software-dep-control --format=json
gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/run.admin"
```

Notes:

- The default output of the add/remove forms already prints `Updated IAM policy for project [...]`; no `--format` is needed for the mutation proof — the independent `get-iam-policy` read-back is the evidence.
- IAM changes need a short propagation window (about a minute) before the granted permission is usable; pre-verify with a cheaper permission proof before the target operation.
- The removal targets exactly the member/role pair that was granted; the final read-back must show no remaining binding for the administering identity.
- Ordering rule when service-account-level bindings are involved: remove them first over `gcloud iam service-accounts remove-iam-policy-binding` and remove the project-level administration role (for example `roles/iam.serviceAccountAdmin`) last — removing it first strands the service-account-level bindings behind `PERMISSION_DENIED`.