# `roles/contactcenterinsights.serviceAgent`

Allows Contact Center AI to read and write APIs including BigQuery, Dialogflow, and Storage.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/contactcenterinsights.serviceAgent` |
| Title | Contact Center AI Insights Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 76 |
| Service | [contactcenterinsights](../overview.md) |

## Permissions

`roles/contactcenterinsights.serviceAgent` grants 76 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 8 |
| [ces](permissions/ces/overview.md) | 18 |
| [datalabeling](permissions/datalabeling/overview.md) | 9 |
| [dialogflow](permissions/dialogflow/overview.md) | 20 |
| [dlp](permissions/dlp/overview.md) | 7 |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [speech](permissions/speech/overview.md) | 7 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/contactcenterinsights.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
