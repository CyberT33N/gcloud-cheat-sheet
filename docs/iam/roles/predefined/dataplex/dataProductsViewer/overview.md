# `roles/dataplex.dataProductsViewer`

Read access to Data Products.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.dataProductsViewer` |
| Title | Dataplex Data Products Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.dataProductsViewer` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.dataProductsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
