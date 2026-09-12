# `roles/resourcemanager.folderViewer`

Access to view a folder and all of its child resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/resourcemanager.folderViewer` |
| Title | Folder Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [resourcemanager](../overview.md) |

## Permissions

`roles/resourcemanager.folderViewer` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [essentialcontacts](permissions/essentialcontacts/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/resourcemanager.folderViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
