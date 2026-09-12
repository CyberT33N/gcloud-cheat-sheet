# `roles/bigquery.securityAdmin`

Administer all BigQuery security controls

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.securityAdmin` |
| Title | BigQuery Security Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 37 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.securityAdmin` grants 37 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 36 |
| [dataplex](permissions/dataplex/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.securityAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
