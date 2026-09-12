# `roles/aiplatform.tuningServiceAgent`

Vertex AI Service Agent used for tuning in user project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.tuningServiceAgent` |
| Title | Vertex AI Tuning Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 94 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.tuningServiceAgent` grants 94 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 70 |
| [bigquery](permissions/bigquery/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.tuningServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
