# `roles/bigquery.resourceAdmin`

Administers BigQuery workloads, including slot assignments, commitments, and reservations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.resourceAdmin` |
| Title | BigQuery Resource Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 37 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.resourceAdmin` grants 37 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 29 |
| [recommender](permissions/recommender/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.resourceAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
