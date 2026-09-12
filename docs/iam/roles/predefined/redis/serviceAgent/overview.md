# `roles/redis.serviceAgent`

Gives Cloud Memorystore Redis service account access to managed resource

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/redis.serviceAgent` |
| Title | Cloud Memorystore Redis Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [redis](../overview.md) |

## Permissions

`roles/redis.serviceAgent` grants 18 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 10 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/redis.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
