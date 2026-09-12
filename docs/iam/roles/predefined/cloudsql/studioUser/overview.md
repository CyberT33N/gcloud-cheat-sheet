# `roles/cloudsql.studioUser`

Role allowing access to Cloud SQL Studio

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsql.studioUser` |
| Title | Cloud SQL Studio User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [cloudsql](../overview.md) |

## Permissions

`roles/cloudsql.studioUser` grants 14 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 4 |
| [cloudsql](permissions/cloudsql/overview.md) | 5 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsql.studioUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
