# Billing

## Projects


### Describe

Multiple:
```shell
Write-Output "== parents + billing" ; foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { $desc = (gcloud projects describe $p --format="value(lifecycleState,parent.type,parent.id)") ; $bill = (gcloud billing projects describe $p --format="value(billingEnabled)") 
```

---

### Link

Multiple:
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== billing test-software-dep-$z =="; gcloud billing projects link "test-software-dep-$z" --billing-account=xxxxxxxxxxxxxxxxx --format="value(billingAccountName,billingEnabled)" }
```