# `roles/cloudsql.admin`

Full control of Cloud SQL resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsql.admin` |
| Title | Cloud SQL Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 173 |
| Service | [cloudsql](../overview.md) |

## Permissions

`roles/cloudsql.admin` grants 173 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 19 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 5 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [cloudsql](permissions/cloudsql/overview.md) | 72 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 8 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 51 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsql.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
