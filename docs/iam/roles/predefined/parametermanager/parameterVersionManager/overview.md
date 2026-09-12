# `roles/parametermanager.parameterVersionManager`

Grants read & write access to all Parameter Manager ParameterVersion resources. Intended for users & applications that need to view Parameters and perform create/read/update/delete/list operations on ParameterVersions only.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parametermanager.parameterVersionManager` |
| Title | Parameter Manager Parameter Version Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [parametermanager](../overview.md) |

## Permissions

`roles/parametermanager.parameterVersionManager` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parametermanager](permissions/parametermanager/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parametermanager.parameterVersionManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
