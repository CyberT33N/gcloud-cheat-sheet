# `roles/redis.editor`

Read-Write access to Redis instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/redis.editor` |
| Title | Cloud Memorystore Redis Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [redis](../overview.md) |

## Permissions

`roles/redis.editor` grants 27 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 1 |
| [redis](permissions/redis/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/redis.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
