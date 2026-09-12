# `roles/iap.admin`

Administrator of IAP Permissions

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iap.admin` |
| Title | IAP Policy Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [iap](../overview.md) |

## Permissions

`roles/iap.admin` grants 18 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iap](permissions/iap/overview.md) | 18 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iap.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
