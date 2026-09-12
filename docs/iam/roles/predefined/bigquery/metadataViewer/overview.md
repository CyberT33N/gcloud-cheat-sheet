# `roles/bigquery.metadataViewer`

Access to view metadata of dataset, table, model, routine, and property graph

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.metadataViewer` |
| Title | BigQuery Metadata Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.metadataViewer` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 11 |
| [dataplex](permissions/dataplex/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.metadataViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
