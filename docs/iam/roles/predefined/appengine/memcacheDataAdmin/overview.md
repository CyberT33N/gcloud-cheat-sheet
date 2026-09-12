# `roles/appengine.memcacheDataAdmin`

Can get, set, delete, and flush App Engine Memcache items.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.memcacheDataAdmin` |
| Title | App Engine Memcache Data Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.memcacheDataAdmin` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.memcacheDataAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
