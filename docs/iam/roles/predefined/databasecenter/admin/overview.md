# `roles/databasecenter.admin`

Admin role for Database Center resource data

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/databasecenter.admin` |
| Title | Database Center Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [databasecenter](../overview.md) |

## Permissions

`roles/databasecenter.admin` grants 23 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [databasecenter](permissions/databasecenter/overview.md) | 14 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/databasecenter.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
