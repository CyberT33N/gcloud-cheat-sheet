# `roles/dataplex.metadataFeedOwner`

Grants access to creating and managing Metadata Feeds. Does not give the right to create/modify Entry Groups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.metadataFeedOwner` |
| Title | Dataplex Metadata Feed Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.metadataFeedOwner` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.metadataFeedOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
