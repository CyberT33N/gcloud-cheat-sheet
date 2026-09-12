# `roles/gkehub.gatewayAdmin`

Full access to Connect Gateway.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.gatewayAdmin` |
| Title | Connect Gateway Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.gatewayAdmin` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 8 |
| [serviceusage](permissions/serviceusage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.gatewayAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
