# `roles/designcenter.applicationViewer`

Readonly access to Application.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/designcenter.applicationViewer` |
| Title | Application Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 87 |
| Service | [designcenter](../overview.md) |

## Permissions

`roles/designcenter.applicationViewer` grants 87 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 4 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [config](permissions/config/overview.md) | 20 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/designcenter.applicationViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
