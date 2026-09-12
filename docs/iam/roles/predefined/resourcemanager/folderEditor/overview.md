# `roles/resourcemanager.folderEditor`

Edit, delete, and undelete a folder and all of its child resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/resourcemanager.folderEditor` |
| Title | Folder Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [resourcemanager](../overview.md) |

## Permissions

`roles/resourcemanager.folderEditor` grants 16 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [essentialcontacts](permissions/essentialcontacts/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/resourcemanager.folderEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
