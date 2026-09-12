# `roles/metastore.metadataEditor`

Access to read and modify the metadata of databases and tables under those databases.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/metastore.metadataEditor` |
| Title | Dataproc Metastore Metadata Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [metastore](../overview.md) |

## Permissions

`roles/metastore.metadataEditor` grants 14 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [metastore](permissions/metastore/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/metastore.metadataEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
