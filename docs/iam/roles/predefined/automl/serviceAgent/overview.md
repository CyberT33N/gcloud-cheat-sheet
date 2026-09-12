# `roles/automl.serviceAgent`

AutoML service agent can act as Cloud Storage admin and export BigQuery tables, which can be backed by Cloud Storage and Cloud Bigtable.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/automl.serviceAgent` |
| Title | AutoML Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [automl](../overview.md) |

## Permissions

`roles/automl.serviceAgent` grants 19 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 9 |
| [bigtable](permissions/bigtable/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/automl.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
