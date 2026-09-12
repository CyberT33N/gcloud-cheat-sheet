# `roles/tpu.viewer`

Read-only access to TPU nodes and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/tpu.viewer` |
| Title | TPU Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [tpu](../overview.md) |

## Permissions

`roles/tpu.viewer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [tpu](permissions/tpu/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/tpu.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
