# `roles/tpu.editor`

Editor access to TPU nodes and related resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/tpu.editor` |
| Title | TPU Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [tpu](../overview.md) |

## Permissions

`roles/tpu.editor` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [tpu](permissions/tpu/overview.md) | 23 |

## Inspect this role live

```shell
gcloud iam roles describe roles/tpu.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
