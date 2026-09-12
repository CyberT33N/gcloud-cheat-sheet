# `roles/chronicle.globalDataAccess`

Grants global access to data i.e. all data can be accessed.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.globalDataAccess` |
| Title | Chronicle API Global Data Access |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.globalDataAccess` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.globalDataAccess --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
