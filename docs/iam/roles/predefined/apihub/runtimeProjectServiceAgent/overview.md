# `roles/apihub.runtimeProjectServiceAgent`

Gives API-Hub Service Account access to runtime project resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apihub.runtimeProjectServiceAgent` |
| Title | API-Hub Runtime Project Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [apihub](../overview.md) |

## Permissions

`roles/apihub.runtimeProjectServiceAgent` grants 49 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 10 |
| [apihub](permissions/apihub/overview.md) | 39 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apihub.runtimeProjectServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
