# `roles/monitoring.metricWriter`

Write-only access to metrics.  This provides exactly the permissions needed by the Stackdriver agent and other systems that send metrics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.metricWriter` |
| Title | Monitoring Metric Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.metricWriter` grants 6 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.metricWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
