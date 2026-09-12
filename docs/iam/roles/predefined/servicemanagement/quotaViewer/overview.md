# `roles/servicemanagement.quotaViewer`

Access to view service quotas.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicemanagement.quotaViewer` |
| Title | Quota Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [servicemanagement](../overview.md) |

## Permissions

`roles/servicemanagement.quotaViewer` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudquotas](permissions/cloudquotas/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicemanagement.quotaViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
