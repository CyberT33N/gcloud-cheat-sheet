# `roles/bigtable.reader`

Read access to data in existing tables; read access to metadata for instances, clusters, and tables, including column families.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigtable.reader` |
| Title | Bigtable Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 40 |
| Service | [bigtable](../overview.md) |

## Permissions

`roles/bigtable.reader` grants 40 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigtable](permissions/bigtable/overview.md) | 35 |
| [monitoring](permissions/monitoring/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigtable.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
