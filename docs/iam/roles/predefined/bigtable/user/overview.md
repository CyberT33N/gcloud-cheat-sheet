# `roles/bigtable.user`

Read and write access to data in existing tables; read access to metadata for instances, clusters, and tables, including column families.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigtable.user` |
| Title | Bigtable User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [bigtable](../overview.md) |

## Permissions

`roles/bigtable.user` grants 42 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigtable](permissions/bigtable/overview.md) | 37 |
| [monitoring](permissions/monitoring/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigtable.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
