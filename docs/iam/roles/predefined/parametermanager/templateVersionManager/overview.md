# `roles/parametermanager.templateVersionManager`

Grants read & write access to all Parameter Manager TemplateVersion resources. Intended for users & applications that need to view Templates and perform create/read/update/delete/list operations on TemplateVersions only.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parametermanager.templateVersionManager` |
| Title | Parameter Manager Template Version Manager |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 11 |
| Service | [parametermanager](../overview.md) |

## Permissions

`roles/parametermanager.templateVersionManager` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parametermanager](permissions/parametermanager/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parametermanager.templateVersionManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
