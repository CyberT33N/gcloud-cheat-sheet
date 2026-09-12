# `roles/bigqueryspark.serviceAgent`

Gives BigQuery Spark access to the service accounts in the user project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigqueryspark.serviceAgent` |
| Title | BigQuery Spark Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [bigqueryspark](../overview.md) |

## Permissions

`roles/bigqueryspark.serviceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigqueryspark.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
