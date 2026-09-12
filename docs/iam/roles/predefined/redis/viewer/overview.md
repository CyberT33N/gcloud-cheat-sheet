# `roles/redis.viewer`

Read-only access to Redis instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/redis.viewer` |
| Title | Cloud Memorystore Redis Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 21 |
| Service | [redis](../overview.md) |

## Permissions

`roles/redis.viewer` grants 21 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [redis](permissions/redis/overview.md) | 18 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/redis.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
