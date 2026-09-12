# `roles/apphub.appManagementViewer`

This role, an aggregation of read permissions across multiple app centric products.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apphub.appManagementViewer` |
| Title | App Management Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1029 |
| Service | [apphub](../overview.md) |

## Permissions

`roles/apphub.appManagementViewer` grants 1029 permissions across 16 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 18 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [config](permissions/config/overview.md) | 20 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 29 |
| [developerconnect](permissions/developerconnect/overview.md) | 8 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 290 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [servicehealth](permissions/servicehealth/overview.md) | 11 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apphub.appManagementViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
