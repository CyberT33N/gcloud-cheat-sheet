# `roles/monitoring.admin`

All current and future monitoring permissions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.admin` |
| Title | Monitoring Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 82 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.admin` grants 82 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 63 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
