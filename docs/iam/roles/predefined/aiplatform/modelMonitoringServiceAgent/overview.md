# `roles/aiplatform.modelMonitoringServiceAgent`

Gives Vertex AI Model Monitoring the permissions it needs to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.modelMonitoringServiceAgent` |
| Title | Vertex AI Model Monitoring Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 26 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.modelMonitoringServiceAgent` grants 26 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 4 |
| [bigquery](permissions/bigquery/overview.md) | 10 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.modelMonitoringServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
