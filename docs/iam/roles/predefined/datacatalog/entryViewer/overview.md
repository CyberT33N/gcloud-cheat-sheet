# `roles/datacatalog.entryViewer`

Read access to entries

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.entryViewer` |
| Title | DataCatalog Entry Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.entryViewer` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.entryViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
