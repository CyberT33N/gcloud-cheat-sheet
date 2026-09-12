# `roles/databasecenter.viewer`

Viewer role for Database Center resource data

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/databasecenter.viewer` |
| Title | Database Center Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [databasecenter](../overview.md) |

## Permissions

`roles/databasecenter.viewer` grants 17 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [databasecenter](permissions/databasecenter/overview.md) | 11 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/databasecenter.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
