# `roles/iam.mlEngineer`

Enables an ML engineer as a power user for using GCP for building and deploying AI based applications.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.mlEngineer` |
| Title | ML Engineer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1333 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.mlEngineer` grants 1333 permissions across 20 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 478 |
| [bigquery](permissions/bigquery/overview.md) | 73 |
| [cloudkms](permissions/cloudkms/overview.md) | 28 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 11 |
| [container](permissions/container/overview.md) | 370 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 12 |
| [dataproc](permissions/dataproc/overview.md) | 55 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 17 |
| [logging](permissions/logging/overview.md) | 26 |
| [monitoring](permissions/monitoring/overview.md) | 30 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 38 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 61 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.mlEngineer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
