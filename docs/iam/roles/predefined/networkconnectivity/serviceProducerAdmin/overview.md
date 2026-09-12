# `roles/networkconnectivity.serviceProducerAdmin`

Service Automation Producer Admin uses information from a consumer request to manage ServiceClasses and ServiceConnectionMaps

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkconnectivity.serviceProducerAdmin` |
| Title | Service Automation Service Producer Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [networkconnectivity](../overview.md) |

## Permissions

`roles/networkconnectivity.serviceProducerAdmin` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkconnectivity.serviceProducerAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
