# `roles/datastudio.workspaceViewer`

Viewer of a Data Studio Workspace

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastudio.workspaceViewer` |
| Title | Data Studio Workspace Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [datastudio](../overview.md) |

## Permissions

`roles/datastudio.workspaceViewer` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastudio](permissions/datastudio/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastudio.workspaceViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
