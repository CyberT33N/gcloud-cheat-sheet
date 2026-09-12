# `roles/cloudtrace.admin`

Admin access to Cloud Trace.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtrace.admin` |
| Title | Cloud Trace Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [cloudtrace](../overview.md) |

## Permissions

`roles/cloudtrace.admin` grants 24 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtrace](permissions/cloudtrace/overview.md) | 15 |
| [observability](permissions/observability/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtrace.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
