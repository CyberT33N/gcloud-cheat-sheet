# `roles/resourcemanager.folderCreator`

Create folder and view all of its sub-resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/resourcemanager.folderCreator` |
| Title | Folder Creator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [resourcemanager](../overview.md) |

## Permissions

`roles/resourcemanager.folderCreator` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [essentialcontacts](permissions/essentialcontacts/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/resourcemanager.folderCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
