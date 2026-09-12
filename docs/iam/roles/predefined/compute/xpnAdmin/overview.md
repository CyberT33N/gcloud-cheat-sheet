# `roles/compute.xpnAdmin`

Can administer shared VPC network (XPN).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.xpnAdmin` |
| Title | Compute Shared VPC Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.xpnAdmin` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.xpnAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
