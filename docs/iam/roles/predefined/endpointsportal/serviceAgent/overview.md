# `roles/endpointsportal.serviceAgent`

Can access information about Endpoints services for consumer portal management, and can read Source Repositories for consumer portal custom content.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/endpointsportal.serviceAgent` |
| Title | Endpoints Portal Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [endpointsportal](../overview.md) |

## Permissions

`roles/endpointsportal.serviceAgent` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [servicemanagement](permissions/servicemanagement/overview.md) | 2 |
| [source](permissions/source/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/endpointsportal.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
