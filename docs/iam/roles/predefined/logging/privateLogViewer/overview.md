# `roles/logging.privateLogViewer`

Access to view all logs, including logs with private contents.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/logging.privateLogViewer` |
| Title | Private Logs Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 28 |
| Service | [logging](../overview.md) |

## Permissions

`roles/logging.privateLogViewer` grants 28 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 26 |
| [observability](permissions/observability/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/logging.privateLogViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
