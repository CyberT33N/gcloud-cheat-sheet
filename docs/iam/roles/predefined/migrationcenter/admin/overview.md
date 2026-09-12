# `roles/migrationcenter.admin`

Full access to Migration Center all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/migrationcenter.admin` |
| Title | Migration Center Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 76 |
| Service | [migrationcenter](../overview.md) |

## Permissions

`roles/migrationcenter.admin` grants 76 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [migrationcenter](permissions/migrationcenter/overview.md) | 60 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [rma](permissions/rma/overview.md) | 13 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/migrationcenter.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
