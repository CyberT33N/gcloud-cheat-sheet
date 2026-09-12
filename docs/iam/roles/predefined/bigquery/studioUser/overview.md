# `roles/bigquery.studioUser`

Combination role of BigQuery Job User, BigQuery Read Session User, Dataform Code Creator, Notebook Runtime User and Dataproc Serverless Editor.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.studioUser` |
| Title | BigQuery Studio User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 95 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.studioUser` grants 95 permissions across 12 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 9 |
| [bigquery](permissions/bigquery/overview.md) | 5 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 13 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 5 |
| [dataform](permissions/dataform/overview.md) | 9 |
| [dataplex](permissions/dataplex/overview.md) | 1 |
| [dataproc](permissions/dataproc/overview.md) | 24 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 17 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 1 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.studioUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
