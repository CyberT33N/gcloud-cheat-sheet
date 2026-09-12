# `roles/aiplatform.telemetryServiceAgent`

Allows Vertex AI Telemetry Service Agent to access telemetry data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.telemetryServiceAgent` |
| Title | Vertex AI Telemetry Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.telemetryServiceAgent` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 3 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.telemetryServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
