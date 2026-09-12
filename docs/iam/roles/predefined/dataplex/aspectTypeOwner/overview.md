# `roles/dataplex.aspectTypeOwner`

Grants access to creating and managing Aspect Types. Does not give the right to create/modify Entries.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.aspectTypeOwner` |
| Title | Dataplex Aspect Type Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.aspectTypeOwner` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 1 |
| [dataplex](permissions/dataplex/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.aspectTypeOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
