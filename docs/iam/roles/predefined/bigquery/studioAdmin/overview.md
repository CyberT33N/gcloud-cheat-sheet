# `roles/bigquery.studioAdmin`

Combination role of BigQuery Admin, Dataform Admin, Notebook Runtime Admin and Dataproc Serverless Editor.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.studioAdmin` |
| Title | BigQuery Studio Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 411 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.studioAdmin` grants 411 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 18 |
| [bigquery](permissions/bigquery/overview.md) | 130 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 79 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 7 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 13 |
| [dataproc](permissions/dataproc/overview.md) | 24 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 17 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 1 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.studioAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
