# `roles/migrationcenter.viewer`

Read-only access to Migration Center all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/migrationcenter.viewer` |
| Title | Migration Center Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 39 |
| Service | [migrationcenter](../overview.md) |

## Permissions

`roles/migrationcenter.viewer` grants 39 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [migrationcenter](permissions/migrationcenter/overview.md) | 29 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [rma](permissions/rma/overview.md) | 7 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/migrationcenter.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
