# `roles/dataplex.catalogEditor`

Write access to catalog resources, including entries, entry groups, and glossaries. Cannot set IAM policies on resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.catalogEditor` |
| Title | Dataplex Catalog Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 93 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.catalogEditor` grants 93 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 1 |
| [dataplex](permissions/dataplex/overview.md) | 90 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.catalogEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
