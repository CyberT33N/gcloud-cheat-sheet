# `roles/iap.httpsResourceAccessor`

Access HTTPS resources which use Identity-Aware Proxy

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iap.httpsResourceAccessor` |
| Title | IAP-secured Web App User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [iap](../overview.md) |

## Permissions

`roles/iap.httpsResourceAccessor` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iap](permissions/iap/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iap.httpsResourceAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
