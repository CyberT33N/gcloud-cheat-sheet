# `roles/tpu.xpnAgent`

Can use shared VPC network (XPN) for the TPU VMs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/tpu.xpnAgent` |
| Title | TPU Shared VPC Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 22 |
| Service | [tpu](../overview.md) |

## Permissions

`roles/tpu.xpnAgent` grants 22 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/tpu.xpnAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
