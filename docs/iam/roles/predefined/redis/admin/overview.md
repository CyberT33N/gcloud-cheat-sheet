# `roles/redis.admin`

Full access to Redis instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/redis.admin` |
| Title | Cloud Memorystore Redis Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 58 |
| Service | [redis](../overview.md) |

## Permissions

`roles/redis.admin` grants 58 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 1 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 1 |
| [redis](permissions/redis/overview.md) | 48 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/redis.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
