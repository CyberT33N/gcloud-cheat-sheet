# `roles/networksecurity.authzServiceAgent`

Allows the Network Security service to access dependent resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networksecurity.authzServiceAgent` |
| Title | Network Security Authz Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [networksecurity](../overview.md) |

## Permissions

`roles/networksecurity.authzServiceAgent` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 4 |
| [networkservices](permissions/networkservices/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networksecurity.authzServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
