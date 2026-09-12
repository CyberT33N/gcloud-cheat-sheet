# `roles/bigquery.readSessionUser`

Access to create and use read sessions

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.readSessionUser` |
| Title | BigQuery Read Session User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.readSessionUser` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.readSessionUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
