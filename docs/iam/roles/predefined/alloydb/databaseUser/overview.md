# `roles/alloydb.databaseUser`

Role allowing access to login as a database user.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.databaseUser` |
| Title | AlloyDB Database User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.databaseUser` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 5 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.databaseUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
