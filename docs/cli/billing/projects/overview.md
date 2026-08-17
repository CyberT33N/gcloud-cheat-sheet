# Billing

## Projects

### Link

#### Multiple
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== billing test-software-dep-$z =="; gcloud billing projects link "test-software-dep-$z" --billing-account=xxxxxxxxxxxxxxxxx --format="value(billingAccountName,billingEnabled)" }
```