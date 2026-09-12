# `roles/dataplex.serviceAgent`

Gives the Dataplex service account access to project resources. This access will be used in data discovery, data management and data workload management.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.serviceAgent` |
| Title | Cloud Dataplex Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 393 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.serviceAgent` grants 393 permissions across 21 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [biglake](permissions/biglake/overview.md) | 5 |
| [bigquery](permissions/bigquery/overview.md) | 130 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [datacatalog](permissions/datacatalog/overview.md) | 9 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 20 |
| [dataproc](permissions/dataproc/overview.md) | 14 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 2 |
| [metastore](permissions/metastore/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 11 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
