# `roles/iam.operationViewer`

Operation user role, with permissions to view and list operations in IAM v3

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.operationViewer` |
| Title | IAM Operation Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.operationViewer` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.operationViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
