# `roles/aiplatform.agentSandboxServiceAgent`

Vertex AI Service Agent used to access Agent Sandbox managed resources in consumer project with restricted permissions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.agentSandboxServiceAgent` |
| Title | Vertex AI Agent Sandbox Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.agentSandboxServiceAgent` grants 8 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.agentSandboxServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
