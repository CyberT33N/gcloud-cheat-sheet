# `roles/cloudtrace.agent`

Agent access to Cloud Trace. Can write trace data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtrace.agent` |
| Title | Cloud Trace Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [cloudtrace](../overview.md) |

## Permissions

`roles/cloudtrace.agent` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtrace.agent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
