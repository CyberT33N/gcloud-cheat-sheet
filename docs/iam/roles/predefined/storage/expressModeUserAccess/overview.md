# `roles/storage.expressModeUserAccess`

Grants permission to Express Mode accounts at the project level so they can read, list, create and delete any object in any of their buckets in Express Mode.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.expressModeUserAccess` |
| Title | Storage Express Mode User Access |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.expressModeUserAccess` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 12 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.expressModeUserAccess --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
