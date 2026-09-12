# `roles/endpoints.serviceAgent`

Gives the Cloud Endpoints service account access to Endpoints services and the ability to act as a service controller.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/endpoints.serviceAgent` |
| Title | Cloud Endpoints Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [endpoints](../overview.md) |

## Permissions

`roles/endpoints.serviceAgent` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [servicemanagement](permissions/servicemanagement/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/endpoints.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
