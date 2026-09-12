# `roles/datalabeling.serviceAgent`

Gives Data Labeling service account read/write access to Cloud Storage, read/write BigQuery, update CMLE model versions, editor access to Annotation service and AutoML service.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datalabeling.serviceAgent` |
| Title | Data Labeling Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 107 |
| Service | [datalabeling](../overview.md) |

## Permissions

`roles/datalabeling.serviceAgent` grants 107 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automl](permissions/automl/overview.md) | 50 |
| [bigquery](permissions/bigquery/overview.md) | 7 |
| [ml](permissions/ml/overview.md) | 34 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datalabeling.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
