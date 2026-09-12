# `roles/datacatalog.searchAdmin`

Can search all metadata for a project/org in DataCatalog

> **Deprecated.** This role is marked `DEPRECATED` in the IAM API.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.searchAdmin` |
| Title | DataCatalog Search Admin |
| Type | Predefined role |
| Launch stage | `DEPRECATED` |
| Included permissions | 5 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.searchAdmin` grants 5 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 1 |
| [dataplex](permissions/dataplex/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.searchAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
