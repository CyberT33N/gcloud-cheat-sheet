# `roles/compute.loadBalancerAdmin`

Full control of Compute Engine resources related to load balancer.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.loadBalancerAdmin` |
| Title | Compute Load Balancer Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 451 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.loadBalancerAdmin` grants 451 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [certificatemanager](permissions/certificatemanager/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 430 |
| [networksecurity](permissions/networksecurity/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.loadBalancerAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
