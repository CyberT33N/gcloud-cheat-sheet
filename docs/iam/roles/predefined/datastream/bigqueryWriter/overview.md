# `roles/datastream.bigqueryWriter`

Permissions needed for datastream to write to BigQuery.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastream.bigqueryWriter` |
| Title | Datastream Bigquery Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 64 |
| Service | [datastream](../overview.md) |

## Permissions

`roles/datastream.bigqueryWriter` grants 64 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 15 |
| [datastream](permissions/datastream/overview.md) | 49 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastream.bigqueryWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
