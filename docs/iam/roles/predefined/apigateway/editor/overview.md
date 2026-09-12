# `roles/apigateway.editor`

Editor role for ApiGateway

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigateway.editor` |
| Title | ApiGateway Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 44 |
| Service | [apigateway](../overview.md) |

## Permissions

`roles/apigateway.editor` grants 44 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigateway](permissions/apigateway/overview.md) | 28 |
| [apihub](permissions/apihub/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigateway.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
