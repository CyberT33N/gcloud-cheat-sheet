# `roles/apigateway.serviceAgent`

Gives Cloud API Gateway service account access to Service Management check and reports as well as impersonation on user-specified service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigateway.serviceAgent` |
| Title | Cloud API Gateway Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [apigateway](../overview.md) |

## Permissions

`roles/apigateway.serviceAgent` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigateway.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
