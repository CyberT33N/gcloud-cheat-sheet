# `roles/apptopology.viewer`

Readonly access to App Topology resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apptopology.viewer` |
| Title | App Topology Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [apptopology](../overview.md) |

## Permissions

`roles/apptopology.viewer` grants 49 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apptopology](permissions/apptopology/overview.md) | 14 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apptopology.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
