# `roles/auditmanager.ccfViewer`

Allows viewing Custom Compliance Framework resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/auditmanager.ccfViewer` |
| Title | Custom Compliance Framework Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 8 |
| Service | [auditmanager](../overview.md) |

## Permissions

`roles/auditmanager.ccfViewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [auditmanager](permissions/auditmanager/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/auditmanager.ccfViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
