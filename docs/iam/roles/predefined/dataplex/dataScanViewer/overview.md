# `roles/dataplex.dataScanViewer`

Read access to DataScan resources, excluding the results.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.dataScanViewer` |
| Title | Dataplex DataScan Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.dataScanViewer` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.dataScanViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
