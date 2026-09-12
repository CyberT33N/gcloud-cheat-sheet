# `roles/compute.publicIpAdmin`

Full control of public IP address management for Compute Engine.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.publicIpAdmin` |
| Title | Compute Public IP Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 51 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.publicIpAdmin` grants 51 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 49 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.publicIpAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
