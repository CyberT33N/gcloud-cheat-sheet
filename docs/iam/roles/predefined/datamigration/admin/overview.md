# `roles/datamigration.admin`

Full access to all resources of Database Migration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datamigration.admin` |
| Title | Database Migration Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 70 |
| Service | [datamigration](../overview.md) |

## Permissions

`roles/datamigration.admin` grants 70 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 1 |
| [datamigration](permissions/datamigration/overview.md) | 66 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datamigration.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
