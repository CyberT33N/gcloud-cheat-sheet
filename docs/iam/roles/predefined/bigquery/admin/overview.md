# `roles/bigquery.admin`

Administer all BigQuery resources and data

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.admin` |
| Title | BigQuery Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 249 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.admin` grants 249 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 130 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
