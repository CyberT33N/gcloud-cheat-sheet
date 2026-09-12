# `roles/securitycenter.issuesViewer`

Read access to security center issues

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.issuesViewer` |
| Title | Security Center Issues Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.issuesViewer` grants 9 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [securitycenter](permissions/securitycenter/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.issuesViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
