# `roles/storage.legacyObjectReader`

Grants permission to view objects and their metadata, excluding ACLs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.legacyObjectReader` |
| Title | Storage Legacy Object Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.legacyObjectReader` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.legacyObjectReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
