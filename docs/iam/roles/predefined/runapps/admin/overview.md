# `roles/runapps.admin`

Admin role for runapps

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/runapps.admin` |
| Title | Runapps Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 17 |
| Service | [runapps](../overview.md) |

## Permissions

`roles/runapps.admin` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [runapps](permissions/runapps/overview.md) | 15 |

## Inspect this role live

```shell
gcloud iam roles describe roles/runapps.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
