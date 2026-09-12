# `roles/gkemulticloud.telemetryWriter`

Grant access to write cluster telemetry data such as logs, metrics, and resource metadata.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkemulticloud.telemetryWriter` |
| Title | Anthos Multi-cloud Telemetry Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [gkemulticloud](../overview.md) |

## Permissions

`roles/gkemulticloud.telemetryWriter` grants 12 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [kubernetesmetadata](permissions/kubernetesmetadata/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkemulticloud.telemetryWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
