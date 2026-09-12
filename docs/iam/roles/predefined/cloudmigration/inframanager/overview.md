# `roles/cloudmigration.inframanager`

Ability to create and manage Compute VMs to run Velostrata Infrastructure

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudmigration.inframanager` |
| Title | Velostrata Manager |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 86 |
| Service | [cloudmigration](../overview.md) |

## Permissions

`roles/cloudmigration.inframanager` grants 86 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudmigration](permissions/cloudmigration/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 76 |
| [gkehub](permissions/gkehub/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudmigration.inframanager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
