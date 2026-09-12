# `roles/vmwareengine.vmwareengineViewer`

Viewer has read-only access to VMware Engine Service

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmwareengine.vmwareengineViewer` |
| Title | VMware Engine Service Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 57 |
| Service | [vmwareengine](../overview.md) |

## Permissions

`roles/vmwareengine.vmwareengineViewer` grants 57 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vmwareengine](permissions/vmwareengine/overview.md) | 55 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmwareengine.vmwareengineViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
