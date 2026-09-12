# `roles/visionai.serviceAgent`

Grants Cloud Vision AI service account permissions to manage resources in consumer project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/visionai.serviceAgent` |
| Title | Cloud Vision AI Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 174 |
| Service | [visionai](../overview.md) |

## Permissions

`roles/visionai.serviceAgent` grants 174 permissions across 12 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 3 |
| [bigquery](permissions/bigquery/overview.md) | 12 |
| [bigtable](permissions/bigtable/overview.md) | 3 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [pubsub](permissions/pubsub/overview.md) | 13 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 14 |
| [visionai](permissions/visionai/overview.md) | 115 |

## Inspect this role live

```shell
gcloud iam roles describe roles/visionai.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
