# `roles/monitoring.viewer`

Read-only access to get and list information about all monitoring data and configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.viewer` |
| Title | Monitoring Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 35 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.viewer` grants 35 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
