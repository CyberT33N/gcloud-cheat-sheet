# `roles/telemetry.serviceTelemetryWriter`

Allows an onboarded service to write all telemetry data to a destination.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/telemetry.serviceTelemetryWriter` |
| Title | Integrated Service Telemetry Writer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [telemetry](../overview.md) |

## Permissions

`roles/telemetry.serviceTelemetryWriter` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [telemetry](permissions/telemetry/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/telemetry.serviceTelemetryWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
