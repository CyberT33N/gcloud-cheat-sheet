# `roles/dataplex.catalogAdmin`

Full access to catalog resources, including entries, entry groups, and glossaries.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.catalogAdmin` |
| Title | Dataplex Catalog Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 110 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.catalogAdmin` grants 110 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 1 |
| [dataplex](permissions/dataplex/overview.md) | 107 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.catalogAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
