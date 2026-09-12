# `roles/monitoring.uptimeCheckConfigViewer`

Read-only access to uptime check configurations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.uptimeCheckConfigViewer` |
| Title | Monitoring Uptime Check Configuration Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.uptimeCheckConfigViewer` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.uptimeCheckConfigViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
