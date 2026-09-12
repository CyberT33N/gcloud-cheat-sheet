# `roles/serviceusage.serviceUsageAdmin`

Ability to enable, disable, and inspect service states, inspect operations, and consume quota and billing for a consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/serviceusage.serviceUsageAdmin` |
| Title | Service Usage Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [serviceusage](../overview.md) |

## Permissions

`roles/serviceusage.serviceUsageAdmin` grants 24 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudquotas](permissions/cloudquotas/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 21 |

## Inspect this role live

```shell
gcloud iam roles describe roles/serviceusage.serviceUsageAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
