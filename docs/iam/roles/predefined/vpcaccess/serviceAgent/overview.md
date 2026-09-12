# `roles/vpcaccess.serviceAgent`

Can create and manage resources to support serverless application to connect to virtual private cloud.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vpcaccess.serviceAgent` |
| Title | Serverless VPC Access Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 99 |
| Service | [vpcaccess](../overview.md) |

## Permissions

`roles/vpcaccess.serviceAgent` grants 99 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 80 |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 12 |
| [logging](permissions/logging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vpcaccess.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
