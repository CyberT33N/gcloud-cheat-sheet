# `roles/securitycenter.adminViewer`

Admin Read access to security center

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.adminViewer` |
| Title | Security Center Admin Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 305 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.adminViewer` grants 305 permissions across 20 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 16 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [assuredoss](permissions/assuredoss/overview.md) | 7 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudasset](permissions/cloudasset/overview.md) | 25 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [cloudsecurityscanner](permissions/cloudsecurityscanner/overview.md) | 8 |
| [dlp](permissions/dlp/overview.md) | 9 |
| [dspm](permissions/dspm/overview.md) | 9 |
| [externalexposure](permissions/externalexposure/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 6 |
| [securitycenter](permissions/securitycenter/overview.md) | 57 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 22 |
| [securityposture](permissions/securityposture/overview.md) | 7 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.adminViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
