# `roles/memcache.serviceAgent`

Gives Cloud Memorystore Memcached service account access to managed resource

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/memcache.serviceAgent` |
| Title | Cloud Memorystore Memcached Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [memcache](../overview.md) |

## Permissions

`roles/memcache.serviceAgent` grants 17 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 9 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/memcache.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
