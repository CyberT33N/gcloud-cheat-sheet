# `roles/workflows.editor`

Read and write access to workflows and related resources, including development and debugging of workflows.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workflows.editor` |
| Title | Workflows Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 30 |
| Service | [workflows](../overview.md) |

## Permissions

`roles/workflows.editor` grants 30 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workflows](permissions/workflows/overview.md) | 23 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workflows.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
