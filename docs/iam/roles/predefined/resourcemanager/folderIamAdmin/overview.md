# `roles/resourcemanager.folderIamAdmin`

Access and administer a folder IAM policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/resourcemanager.folderIamAdmin` |
| Title | Folder IAM Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [resourcemanager](../overview.md) |

## Permissions

`roles/resourcemanager.folderIamAdmin` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/resourcemanager.folderIamAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
