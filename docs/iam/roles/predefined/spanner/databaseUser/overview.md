# `roles/spanner.databaseUser`

Access to read, query, write and view and change the schema of Cloud Spanner databases

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.databaseUser` |
| Title | Cloud Spanner Database User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.databaseUser` grants 23 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.databaseUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
