# Billing

## Projects

### Link

#### Multiple
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== billing t33n-software-dep-$z =="; gcloud billing projects link "t33n-software-dep-$z" --billing-account=xxxxxxxxxxxxxxxxx --format="value(billingAccountName,billingEnabled)" }
```