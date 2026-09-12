# `roles/compute.instanceGroupManagerServiceAgent`

Role containing all permissions required by Managed Instance Groups to create and managed instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.instanceGroupManagerServiceAgent` |
| Title | Instance Group Manager Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 118 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.instanceGroupManagerServiceAgent` grants 118 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 113 |
| [iam](permissions/iam/overview.md) | 1 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.instanceGroupManagerServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
