# `roles/cloudscheduler.jobRunner`

Access to run jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudscheduler.jobRunner` |
| Title | Cloud Scheduler Job Runner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [cloudscheduler](../overview.md) |

## Permissions

`roles/cloudscheduler.jobRunner` grants 14 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [cloudscheduler](permissions/cloudscheduler/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudscheduler.jobRunner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
