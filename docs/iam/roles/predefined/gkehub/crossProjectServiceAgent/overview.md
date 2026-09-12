# `roles/gkehub.crossProjectServiceAgent`

Gives the GKE Hub service agent permission to manage the project for cross-project fleet registration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.crossProjectServiceAgent` |
| Title | GKE Hub Cross Project Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.crossProjectServiceAgent` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.crossProjectServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
