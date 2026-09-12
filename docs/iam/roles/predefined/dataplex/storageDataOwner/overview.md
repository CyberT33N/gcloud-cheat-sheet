# `roles/dataplex.storageDataOwner`

Owner access to data.  Should not be used directly. This role is granted by Dataplex Universal Catalog to managed resources like Cloud Storage buckets, BigQuery datasets etc.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.storageDataOwner` |
| Title | Dataplex Storage Data Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 31 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.storageDataOwner` grants 31 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 25 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.storageDataOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
