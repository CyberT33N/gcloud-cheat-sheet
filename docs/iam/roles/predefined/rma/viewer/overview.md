# `roles/rma.viewer`

Read-only access to Rapid Migration Assessment all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/rma.viewer` |
| Title | Rapid Migration Assessment Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [rma](../overview.md) |

## Permissions

`roles/rma.viewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [rma](permissions/rma/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/rma.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
