# `roles/designcenter.viewer`

Readonly access to Application Design Center resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/designcenter.viewer` |
| Title | Application Design Center Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 84 |
| Service | [designcenter](../overview.md) |

## Permissions

`roles/designcenter.viewer` grants 84 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 29 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/designcenter.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
