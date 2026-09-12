# `roles/dataform.codeCommenter`

Permissions to comment, at the repository level. Grants CRUD access over commentThread and comment resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataform.codeCommenter` |
| Title | Code Commenter |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 17 |
| Service | [dataform](../overview.md) |

## Permissions

`roles/dataform.codeCommenter` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataform](permissions/dataform/overview.md) | 15 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataform.codeCommenter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
