# `roles/metastore.metadataViewer`

Access to read the metadata of databases and tables under those databases

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/metastore.metadataViewer` |
| Title | Dataproc Metastore Metadata Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [metastore](../overview.md) |

## Permissions

`roles/metastore.metadataViewer` grants 8 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [metastore](permissions/metastore/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/metastore.metadataViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
