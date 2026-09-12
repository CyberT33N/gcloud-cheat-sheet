# `roles/gkemulticloud.containerServiceAgent`

Grants the Anthos Multi-Cloud Container Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkemulticloud.containerServiceAgent` |
| Title | Anthos Multi-Cloud Container Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [gkemulticloud](../overview.md) |

## Permissions

`roles/gkemulticloud.containerServiceAgent` grants 49 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 5 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [kubernetesmetadata](permissions/kubernetesmetadata/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 31 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkemulticloud.containerServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
