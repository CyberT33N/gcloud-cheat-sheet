# `roles/monitoring.metricsScopesAdmin`

Access to add and remove monitored projects from metrics scopes.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.metricsScopesAdmin` |
| Title | Monitoring Metrics Scopes Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.metricsScopesAdmin` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.metricsScopesAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
