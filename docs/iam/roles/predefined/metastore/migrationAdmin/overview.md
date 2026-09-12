# `roles/metastore.migrationAdmin`

Access to Dataproc Metastore Managed Migration resources and workflow.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/metastore.migrationAdmin` |
| Title | Dataproc Metastore Managed Migration Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [metastore](../overview.md) |

## Permissions

`roles/metastore.migrationAdmin` grants 49 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudsql](permissions/cloudsql/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 33 |
| [datastream](permissions/datastream/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/metastore.migrationAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
