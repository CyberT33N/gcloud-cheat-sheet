# `roles/gkehub.scopeAdmin`

Admin access to Fleet Scopes to set IAM Bindings and RBACRoleBindings.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.scopeAdmin` |
| Title | Fleet Scope Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.scopeAdmin` grants 13 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.scopeAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
