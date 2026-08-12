# IAM

## Service Accounts

### IAM
- docs\cli\iam\service-accounts\iam\overview.md

### create 
```shell
gcloud iam service-accounts create gba-builder-staging-deployer --project=test-go-builder-authority --display-name="GBA Builder Staging Deployer" --description="Writes only staging Go builder artifacts and evidence" --quiet
```




### keys

#### list

```shell
gcloud iam service-accounts keys list --iam-account=gba-builder-staging-deployer@cybert33n-go-builder-authority.iam.gserviceaccount.com --project=test-go-builder-authority --format="table(name.basename(),keyType,keyOrigin)"
```
