# `roles/servicemanagement.viewer`

Viewer role for Service Management.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicemanagement.viewer` |
| Title | Service Management Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [servicemanagement](../overview.md) |

## Permissions

`roles/servicemanagement.viewer` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicemanagement.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
