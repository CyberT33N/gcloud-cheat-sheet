# `roles/networkservices.serviceExtensionsViewer`

Provides read-only access to Service Extensions resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkservices.serviceExtensionsViewer` |
| Title | Service Extensions Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 17 |
| Service | [networkservices](../overview.md) |

## Permissions

`roles/networkservices.serviceExtensionsViewer` grants 17 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [networkservices](permissions/networkservices/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkservices.serviceExtensionsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
