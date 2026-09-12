# `roles/spanner.databaseReaderWithDataBoost`

Includes all permissions in the spanner.databaseReader role enabling access to read and/or query a Cloud Spanner database using instance resources, as well as the permission to access the database with Data Boost, a fully managed serverless service that provides independent compute resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.databaseReaderWithDataBoost` |
| Title | Cloud Spanner Database Reader with DataBoost |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.databaseReaderWithDataBoost` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.databaseReaderWithDataBoost --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
