# `roles/cloudprivatecatalogproducer.manager`

Can manage associations between a catalog and a target resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudprivatecatalogproducer.manager` |
| Title | Catalog Manager |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 20 |
| Service | [cloudprivatecatalogproducer](../overview.md) |

## Permissions

`roles/cloudprivatecatalogproducer.manager` grants 20 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudprivatecatalog](permissions/cloudprivatecatalog/overview.md) | 1 |
| [cloudprivatecatalogproducer](permissions/cloudprivatecatalogproducer/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudprivatecatalogproducer.manager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
