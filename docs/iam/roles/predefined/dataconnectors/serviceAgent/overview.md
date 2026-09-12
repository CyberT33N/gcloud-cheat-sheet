# `roles/dataconnectors.serviceAgent`

Gives Data Connectors service agent permission to access the virtual private cloud

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataconnectors.serviceAgent` |
| Title | Data Connectors Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [dataconnectors](../overview.md) |

## Permissions

`roles/dataconnectors.serviceAgent` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 2 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataconnectors.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
