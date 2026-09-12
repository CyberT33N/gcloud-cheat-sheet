# `roles/storage.legacyObjectOwner`

Grants permission to view and edit objects and their metadata, including ACLs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.legacyObjectOwner` |
| Title | Storage Legacy Object Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.legacyObjectOwner` grants 9 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.legacyObjectOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
