# `roles/datastore.backupsAdmin`

Read/Write access to metadata about backups in Cloud Datastore but restore is not allowed.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastore.backupsAdmin` |
| Title | Cloud Datastore Backups Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [datastore](../overview.md) |

## Permissions

`roles/datastore.backupsAdmin` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastore](permissions/datastore/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastore.backupsAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
