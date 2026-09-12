# `roles/aiplatform.serviceAgent`

Gives Vertex AI the permissions it needs to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.serviceAgent` |
| Title | Vertex AI Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 635 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.serviceAgent` grants 635 permissions across 24 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentregistry](permissions/agentregistry/overview.md) | 12 |
| [aiplatform](permissions/aiplatform/overview.md) | 449 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 7 |
| [automl](permissions/automl/overview.md) | 8 |
| [bigquery](permissions/bigquery/overview.md) | 17 |
| [bigtable](permissions/bigtable/overview.md) | 3 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 42 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [datalabeling](permissions/datalabeling/overview.md) | 5 |
| [hypercomputecluster](permissions/hypercomputecluster/overview.md) | 11 |
| [iam](permissions/iam/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 10 |
| [ml](permissions/ml/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [networkservices](permissions/networkservices/overview.md) | 3 |
| [notebooks](permissions/notebooks/overview.md) | 3 |
| [observability](permissions/observability/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 13 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
