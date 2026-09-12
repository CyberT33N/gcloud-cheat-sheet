# `roles/monitoring.notificationServiceAgent`

Grants Cloud Monitoring and Cloud Alerting permission to access consumer resources and track usage.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.notificationServiceAgent` |
| Title | Monitoring Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.notificationServiceAgent` grants 17 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 1 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 8 |
| [observability](permissions/observability/overview.md) | 1 |
| [run](permissions/run/overview.md) | 1 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.notificationServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
