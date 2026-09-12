# `roles/iam.organizationRoleViewer`

Read access to all custom roles in the organization and the projects below it.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.organizationRoleViewer` |
| Title | Organization Role Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.organizationRoleViewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.organizationRoleViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
