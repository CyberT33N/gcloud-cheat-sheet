# `roles/servicenetworking.serviceAgent`

Gives permission to manage network configuration, such as establishing network peering, necessary for service producers

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicenetworking.serviceAgent` |
| Title | Service Networking Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 68 |
| Service | [servicenetworking](../overview.md) |

## Permissions

`roles/servicenetworking.serviceAgent` grants 68 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 22 |
| [dns](permissions/dns/overview.md) | 43 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicenetworking.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
