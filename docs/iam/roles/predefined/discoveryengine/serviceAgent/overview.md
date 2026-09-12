# `roles/discoveryengine.serviceAgent`

Discovery Engine service uploads documents and user events from Cloud Storage and BigQuery, reports results to the customer Cloud Storage bucket, writes logs to customer projects using Cloud Logging, and writes and reads metrics for customer using Cloud Monitoring.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.serviceAgent` |
| Title | Discovery Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 119 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.serviceAgent` grants 119 permissions across 19 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentregistry](permissions/agentregistry/overview.md) | 10 |
| [aiplatform](permissions/aiplatform/overview.md) | 24 |
| [alloydb](permissions/alloydb/overview.md) | 4 |
| [bigquery](permissions/bigquery/overview.md) | 13 |
| [bigtable](permissions/bigtable/overview.md) | 2 |
| [cloudsql](permissions/cloudsql/overview.md) | 3 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 1 |
| [datastore](permissions/datastore/overview.md) | 4 |
| [dialogflow](permissions/dialogflow/overview.md) | 1 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 9 |
| [integrations](permissions/integrations/overview.md) | 12 |
| [logging](permissions/logging/overview.md) | 1 |
| [modelarmor](permissions/modelarmor/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [networkservices](permissions/networkservices/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceextensions](permissions/serviceextensions/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 5 |
| [storage](permissions/storage/overview.md) | 15 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
