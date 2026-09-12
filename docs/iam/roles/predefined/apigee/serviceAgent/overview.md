# `roles/apigee.serviceAgent`

Service agent that grants access to Apigee resources - API Products, Developers, Developer Apps, and App Keys.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.serviceAgent` |
| Title | Apigee Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 86 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.serviceAgent` grants 86 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 26 |
| [apihub](permissions/apihub/overview.md) | 43 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 7 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
