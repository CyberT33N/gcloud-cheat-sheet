# `roles/capacityplanner.viewer`

Read-only access to Capacity Planner resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/capacityplanner.viewer` |
| Title | Capacity Planner Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 25 |
| Service | [capacityplanner](../overview.md) |

## Permissions

`roles/capacityplanner.viewer` grants 25 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [capacityplanner](permissions/capacityplanner/overview.md) | 8 |
| [cloudquotas](permissions/cloudquotas/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/capacityplanner.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
