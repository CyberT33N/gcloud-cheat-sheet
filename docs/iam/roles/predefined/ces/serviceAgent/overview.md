# `roles/ces.serviceAgent`

Allows Customer Engagement Suite Service Account to access to dependent resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ces.serviceAgent` |
| Title | Customer Engagement Suite Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 182 |
| Service | [ces](../overview.md) |

## Permissions

`roles/ces.serviceAgent` grants 182 permissions across 14 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 16 |
| [bigquery](permissions/bigquery/overview.md) | 9 |
| [ces](permissions/ces/overview.md) | 62 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 1 |
| [connectors](permissions/connectors/overview.md) | 15 |
| [contactcenterinsights](permissions/contactcenterinsights/overview.md) | 39 |
| [dialogflow](permissions/dialogflow/overview.md) | 2 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 18 |
| [dlp](permissions/dlp/overview.md) | 7 |
| [integrations](permissions/integrations/overview.md) | 4 |
| [logging](permissions/logging/overview.md) | 2 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ces.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
