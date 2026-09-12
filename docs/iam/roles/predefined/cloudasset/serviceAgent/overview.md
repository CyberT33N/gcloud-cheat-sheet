# `roles/cloudasset.serviceAgent`

Gives Cloud Asset service agent permissions to Cloud Storage and BigQuery for exporting Assets, and permission to publish to Cloud Pub/Sub topics for Asset Real Time Feed.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudasset.serviceAgent` |
| Title | Cloud Asset Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [cloudasset](../overview.md) |

## Permissions

`roles/cloudasset.serviceAgent` grants 15 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 8 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudasset.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
