# `roles/timeseriesinsights.admin`

Admin role for timeseriesinsights

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/timeseriesinsights.admin` |
| Title | Timeseriesinsights Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 10 |
| Service | [timeseriesinsights](../overview.md) |

## Permissions

`roles/timeseriesinsights.admin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [timeseriesinsights](permissions/timeseriesinsights/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/timeseriesinsights.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
