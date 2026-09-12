# `roles/monitoring.alertPolicyViewer`

Read-only access to alerting policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/monitoring.alertPolicyViewer` |
| Title | Monitoring AlertPolicy Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [monitoring](../overview.md) |

## Permissions

`roles/monitoring.alertPolicyViewer` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/monitoring.alertPolicyViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
