# `roles/metastore.editor`

Read and write access to all Dataproc Metastore resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/metastore.editor` |
| Title | Dataproc Metastore Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [metastore](../overview.md) |

## Permissions

`roles/metastore.editor` grants 42 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [metastore](permissions/metastore/overview.md) | 40 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/metastore.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
