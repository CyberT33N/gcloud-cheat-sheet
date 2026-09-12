# `roles/apigateway_management.serviceAgent`

Gives Cloud API Gateway service account access to retrieve aService configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigateway_management.serviceAgent` |
| Title | Cloud API Gateway Management Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [apigateway_management](../overview.md) |

## Permissions

`roles/apigateway_management.serviceAgent` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 1 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 5 |
| [serviceusage](permissions/serviceusage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigateway_management.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
