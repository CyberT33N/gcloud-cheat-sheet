# `roles/tpu.admin`

Full access to TPU nodes and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/tpu.admin` |
| Title | TPU Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [tpu](../overview.md) |

## Permissions

`roles/tpu.admin` grants 27 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [tpu](permissions/tpu/overview.md) | 25 |

## Inspect this role live

```shell
gcloud iam roles describe roles/tpu.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
