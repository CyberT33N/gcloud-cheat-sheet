# `roles/bigquery.resourceEditor`

Manages BigQuery workloads, but is unable to create or modify slot commitments.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.resourceEditor` |
| Title | BigQuery Resource Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.resourceEditor` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.resourceEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
