# `roles/bigquery.user`

When applied to a project, access to run queries, create datasets, read dataset metadata, and list tables, models and property graphs. When applied to a dataset, access to read dataset metadata and list tables, models, routines and property graphs within the dataset.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.user` |
| Title | BigQuery User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.user` grants 41 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 27 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
