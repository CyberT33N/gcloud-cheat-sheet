# `roles/automlrecommendations.serviceAgent`

Recommendations AI service uploads catalog feeds from Cloud Storage, reports results to the customer Cloud Storage bucket, writes logs to customer projects, and writes and reads Stackdriver metrics for customer projects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/automlrecommendations.serviceAgent` |
| Title | Recommendations AI Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 67 |
| Service | [automlrecommendations](../overview.md) |

## Permissions

`roles/automlrecommendations.serviceAgent` grants 67 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 13 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [dataflow](permissions/dataflow/overview.md) | 8 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 31 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/automlrecommendations.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
