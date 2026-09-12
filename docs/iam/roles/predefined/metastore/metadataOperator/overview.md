# `roles/metastore.metadataOperator`

Read-only access to Dataproc Metastore resources with additional metadata operations permission.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/metastore.metadataOperator` |
| Title | Dataproc Metastore Metadata Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 22 |
| Service | [metastore](../overview.md) |

## Permissions

`roles/metastore.metadataOperator` grants 22 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [metastore](permissions/metastore/overview.md) | 20 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/metastore.metadataOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
