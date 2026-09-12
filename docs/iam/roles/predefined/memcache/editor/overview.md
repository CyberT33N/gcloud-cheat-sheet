# `roles/memcache.editor`

Read-Write access to Memcached instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/memcache.editor` |
| Title | Cloud Memorystore Memcached Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [memcache](../overview.md) |

## Permissions

`roles/memcache.editor` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [memcache](permissions/memcache/overview.md) | 15 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/memcache.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
