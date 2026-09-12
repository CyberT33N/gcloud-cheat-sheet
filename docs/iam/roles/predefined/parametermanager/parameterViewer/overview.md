# `roles/parametermanager.parameterViewer`

Grants read access to Parameter Manager Parameter & ParameterVersion resources. Intended for users & applications that need to perform read/list operations on Parameters and ParameterVersions only.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parametermanager.parameterViewer` |
| Title | Parameter Manager Parameter Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [parametermanager](../overview.md) |

## Permissions

`roles/parametermanager.parameterViewer` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parametermanager](permissions/parametermanager/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parametermanager.parameterViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
