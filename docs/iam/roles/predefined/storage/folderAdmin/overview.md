# `roles/storage.folderAdmin`

Grants full control over folders and objects, including listing, creating, viewing, and deleting objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.folderAdmin` |
| Title | Storage Folder Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.folderAdmin` grants 33 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 30 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.folderAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
