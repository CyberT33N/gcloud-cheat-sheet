# `roles/redisenterprisecloud.admin`

This role is managed by Redis Labs, not Google.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/redisenterprisecloud.admin` |
| Title | Redis Enterprise Cloud Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [redisenterprisecloud](../overview.md) |

## Permissions

`roles/redisenterprisecloud.admin` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gcp.redisenterprise.com](permissions/gcp.redisenterprise.com/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/redisenterprisecloud.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
