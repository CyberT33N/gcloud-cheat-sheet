# `roles/bigquerydatatransfer.serviceAgent`

Gives BigQuery Data Transfer Service access to start bigquery jobs in consumer project. 

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquerydatatransfer.serviceAgent` |
| Title | BigQuery Data Transfer Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 36 |
| Service | [bigquerydatatransfer](../overview.md) |

## Permissions

`roles/bigquerydatatransfer.serviceAgent` grants 36 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 4 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 17 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquerydatatransfer.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
