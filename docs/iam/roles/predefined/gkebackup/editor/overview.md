# `roles/gkebackup.editor`

Editor role for gkebackup

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkebackup.editor` |
| Title | Gkebackup Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [gkebackup](../overview.md) |

## Permissions

`roles/gkebackup.editor` grants 49 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkebackup](permissions/gkebackup/overview.md) | 47 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkebackup.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
