# `roles/cloudmigration.velostrataconnect`

Ability to set up connection between Velostrata Manager and Google

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudmigration.velostrataconnect` |
| Title | Velostrata Manager Connection Agent |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [cloudmigration](../overview.md) |

## Permissions

`roles/cloudmigration.velostrataconnect` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudmigration](permissions/cloudmigration/overview.md) | 1 |
| [gkehub](permissions/gkehub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudmigration.velostrataconnect --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
