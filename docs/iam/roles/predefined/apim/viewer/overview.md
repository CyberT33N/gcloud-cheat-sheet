# `roles/apim.viewer`

Readonly access to API Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apim.viewer` |
| Title | API Management Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 16 |
| Service | [apim](../overview.md) |

## Permissions

`roles/apim.viewer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apim](permissions/apim/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apim.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
