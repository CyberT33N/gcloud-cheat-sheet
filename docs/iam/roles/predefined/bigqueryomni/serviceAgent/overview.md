# `roles/bigqueryomni.serviceAgent`

Gives BigQuery Omni access to tables in user projects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigqueryomni.serviceAgent` |
| Title | BigQuery Omni Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [bigqueryomni](../overview.md) |

## Permissions

`roles/bigqueryomni.serviceAgent` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigqueryomni.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
