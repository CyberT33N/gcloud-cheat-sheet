# `roles/dataprocrm.nodeServiceAgent`

Dataproc Resource Manager Node Service Agent used to run managed resources in user project with restricted permissions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataprocrm.nodeServiceAgent` |
| Title | Dataproc Resource Manager Node Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [dataprocrm](../overview.md) |

## Permissions

`roles/dataprocrm.nodeServiceAgent` grants 12 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataprocrm](permissions/dataprocrm/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataprocrm.nodeServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
