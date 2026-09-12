# `roles/autoscaling.editor`

Editor role for autoscaling

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/autoscaling.editor` |
| Title | Autoscaling Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 6 |
| Service | [autoscaling](../overview.md) |

## Permissions

`roles/autoscaling.editor` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/autoscaling.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
