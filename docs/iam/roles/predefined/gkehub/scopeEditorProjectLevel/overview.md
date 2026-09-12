# `roles/gkehub.scopeEditorProjectLevel`

Role for project-level permissions for editor of Fleet Scopes.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.scopeEditorProjectLevel` |
| Title | Fleet Project-level Scope Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.scopeEditorProjectLevel` grants 19 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 8 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.scopeEditorProjectLevel --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
