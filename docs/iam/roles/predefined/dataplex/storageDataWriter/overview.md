# `roles/dataplex.storageDataWriter`

Write access to data. Should not be used directly. This role is granted by Dataplex Universal Catalog to managed resources like Cloud Storage buckets, BigQuery datasets etc.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.storageDataWriter` |
| Title | Dataplex Storage Data Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.storageDataWriter` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.storageDataWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
