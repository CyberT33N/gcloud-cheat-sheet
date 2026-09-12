# `roles/aiplatform.customCodeServiceAgent`

Gives Vertex AI Custom Code the proper permissions. The aiplatform.customJobs.create IAM permission is highly privileged. Through Vertex AI Custom Training jobs, it effectively grants editor-level access to other services activated for the consumer project, such as GCS and BigQuery.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.customCodeServiceAgent` |
| Title | Vertex AI Custom Code Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 498 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.customCodeServiceAgent` grants 498 permissions across 12 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 449 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 5 |
| [bigquery](permissions/bigquery/overview.md) | 12 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [observability](permissions/observability/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.customCodeServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
