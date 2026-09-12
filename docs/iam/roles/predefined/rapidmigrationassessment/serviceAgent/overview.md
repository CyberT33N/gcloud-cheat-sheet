# `roles/rapidmigrationassessment.serviceAgent`

Gives RMA service account access to MC resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/rapidmigrationassessment.serviceAgent` |
| Title | RMA Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [rapidmigrationassessment](../overview.md) |

## Permissions

`roles/rapidmigrationassessment.serviceAgent` grants 17 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 1 |
| [migrationcenter](permissions/migrationcenter/overview.md) | 9 |
| [monitoring](permissions/monitoring/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/rapidmigrationassessment.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
