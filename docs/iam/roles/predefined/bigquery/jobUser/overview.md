# `roles/bigquery.jobUser`

Access to run jobs

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.jobUser` |
| Title | BigQuery Job User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.jobUser` grants 10 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 2 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.jobUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
