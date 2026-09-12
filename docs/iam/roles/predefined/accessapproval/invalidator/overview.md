# `roles/accessapproval.invalidator`

Ability to invalidate existing approved approval requests

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/accessapproval.invalidator` |
| Title | Access Approval Invalidator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [accessapproval](../overview.md) |

## Permissions

`roles/accessapproval.invalidator` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accessapproval](permissions/accessapproval/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/accessapproval.invalidator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
