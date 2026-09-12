# `roles/dataplex.entryGroupImporter`

Grants access to import this entry group for Metadata Job processing.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.entryGroupImporter` |
| Title | Dataplex Entry Group Importer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.entryGroupImporter` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.entryGroupImporter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
