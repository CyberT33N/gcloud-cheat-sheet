# `roles/apigee.apimServiceExtensionServiceAgent`

Service agent that grants access to the resources for managing the lifecyle for Apigee APIM Service Extensions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.apimServiceExtensionServiceAgent` |
| Title | Apigee APIM Service Extension Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.apimServiceExtensionServiceAgent` grants 33 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 27 |
| [networkservices](permissions/networkservices/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.apimServiceExtensionServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
