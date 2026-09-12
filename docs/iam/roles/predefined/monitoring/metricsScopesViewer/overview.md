# `roles/monitoring.metricsScopesViewer`

Read-only access to metrics scopes and their monitored projects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.metricsScopesViewer` |
| Title | Monitoring Metrics Scopes Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.metricsScopesViewer` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.metricsScopesViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
