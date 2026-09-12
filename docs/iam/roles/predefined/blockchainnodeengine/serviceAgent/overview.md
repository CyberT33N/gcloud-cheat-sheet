# `roles/blockchainnodeengine.serviceAgent`

Grants Blockchain Node Engine access to metrics in user project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/blockchainnodeengine.serviceAgent` |
| Title | Blockchain Node Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [blockchainnodeengine](../overview.md) |

## Permissions

`roles/blockchainnodeengine.serviceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/blockchainnodeengine.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
