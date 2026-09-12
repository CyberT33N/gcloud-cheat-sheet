# `roles/dialogflow.serviceAgent`

Gives Dialogflow Service Account access to resources on behalf of user project for Integrations (Facebook Messenger, Slack, Telephony, etc.), BigQuery, Discovery Engine, Integration Connectors, Application Integration, and Vertex.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dialogflow.serviceAgent` |
| Title | Dialogflow Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 187 |
| Service | [dialogflow](../overview.md) |

## Permissions

`roles/dialogflow.serviceAgent` grants 187 permissions across 17 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 5 |
| [bigquery](permissions/bigquery/overview.md) | 6 |
| [ces](permissions/ces/overview.md) | 6 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 1 |
| [connectors](permissions/connectors/overview.md) | 15 |
| [dialogflow](permissions/dialogflow/overview.md) | 96 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 17 |
| [dlp](permissions/dlp/overview.md) | 4 |
| [integrations](permissions/integrations/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 2 |
| [pubsub](permissions/pubsub/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [speakerid](permissions/speakerid/overview.md) | 9 |
| [speech](permissions/speech/overview.md) | 7 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dialogflow.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
