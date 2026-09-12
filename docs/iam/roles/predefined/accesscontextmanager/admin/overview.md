# `roles/accesscontextmanager.admin`

Admin role for accesscontextmanager

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/accesscontextmanager.admin` |
| Title | Accesscontextmanager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [accesscontextmanager](../overview.md) |

## Permissions

`roles/accesscontextmanager.admin` grants 33 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accesscontextmanager](permissions/accesscontextmanager/overview.md) | 30 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/accesscontextmanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
