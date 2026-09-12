# `roles/chronicle.restrictedDataAccessViewer`

Grants readonly access to Chronicle API resources without global data access scope.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.restrictedDataAccessViewer` |
| Title | Chronicle API Restricted Data Access Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 117 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.restrictedDataAccessViewer` grants 117 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 115 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.restrictedDataAccessViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
