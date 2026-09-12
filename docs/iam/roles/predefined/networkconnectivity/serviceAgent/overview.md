# `roles/networkconnectivity.serviceAgent`

Grants the Network Connectivity API authority to read some networking resources. It does not mutate these resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkconnectivity.serviceAgent` |
| Title | Network Connectivity Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 62 |
| Service | [networkconnectivity](../overview.md) |

## Permissions

`roles/networkconnectivity.serviceAgent` grants 62 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 33 |
| [dns](permissions/dns/overview.md) | 14 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 10 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkconnectivity.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
