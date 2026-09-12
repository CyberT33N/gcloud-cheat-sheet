# `roles/spanner.restoreAdmin`

Administrator role to restore Cloud Spanner databases from Cloud Spanner backups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.restoreAdmin` |
| Title | Cloud Spanner Restore Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.restoreAdmin` grants 20 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [spanner](permissions/spanner/overview.md) | 17 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.restoreAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
