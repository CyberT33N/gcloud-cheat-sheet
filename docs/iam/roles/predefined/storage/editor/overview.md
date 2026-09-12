# `roles/storage.editor`

Editor role for storage

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.editor` |
| Title | Storage Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.editor` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 23 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
