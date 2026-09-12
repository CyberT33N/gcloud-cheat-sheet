# `roles/aiplatform.reasoningEngineServiceAgent`

Gives Vertex AI Reasoning Engine the proper permissions to function. The aiplatform.reasoningEngines.create IAM permission implies read access to the GCS objects of the consumer project through this service agent.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.reasoningEngineServiceAgent` |
| Title | Vertex AI Reasoning Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 56 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.reasoningEngineServiceAgent` grants 56 permissions across 11 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 23 |
| [cloudapiregistry](permissions/cloudapiregistry/overview.md) | 6 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [developerconnect](permissions/developerconnect/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [modelarmor](permissions/modelarmor/overview.md) | 7 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 4 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.reasoningEngineServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
