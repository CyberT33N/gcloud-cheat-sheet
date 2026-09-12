# `roles/cloudtasks.viewer`

Get and list access to tasks, queues, and locations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtasks.viewer` |
| Title | Cloud Tasks Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [cloudtasks](../overview.md) |

## Permissions

`roles/cloudtasks.viewer` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtasks](permissions/cloudtasks/overview.md) | 9 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtasks.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
