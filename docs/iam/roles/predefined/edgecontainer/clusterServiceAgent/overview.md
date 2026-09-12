# `roles/edgecontainer.clusterServiceAgent`

Grants the Edge Container Cluster Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/edgecontainer.clusterServiceAgent` |
| Title | Edge Container Cluster Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 90 |
| Service | [edgecontainer](../overview.md) |

## Permissions

`roles/edgecontainer.clusterServiceAgent` grants 90 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [gkehub](permissions/gkehub/overview.md) | 20 |
| [kubernetesmetadata](permissions/kubernetesmetadata/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 34 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 15 |
| [stackdriver](permissions/stackdriver/overview.md) | 3 |
| [storage](permissions/storage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/edgecontainer.clusterServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
