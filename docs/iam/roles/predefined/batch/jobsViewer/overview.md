# `roles/batch.jobsViewer`

Viewer of Batch Jobs, Task Groups and Tasks

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/batch.jobsViewer` |
| Title | Batch Job Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [batch](../overview.md) |

## Permissions

`roles/batch.jobsViewer` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [batch](permissions/batch/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/batch.jobsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
