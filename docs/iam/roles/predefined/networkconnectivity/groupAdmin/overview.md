# `roles/networkconnectivity.groupAdmin`

Enables full access to group resources and read-only access to hub and spoke resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkconnectivity.groupAdmin` |
| Title | Group Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [networkconnectivity](../overview.md) |

## Permissions

`roles/networkconnectivity.groupAdmin` grants 29 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 27 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkconnectivity.groupAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
