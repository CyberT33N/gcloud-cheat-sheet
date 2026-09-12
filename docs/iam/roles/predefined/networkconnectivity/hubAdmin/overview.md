# `roles/networkconnectivity.hubAdmin`

Enables full access to hub and spoke resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkconnectivity.hubAdmin` |
| Title | Hub & Spoke Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 54 |
| Service | [networkconnectivity](../overview.md) |

## Permissions

`roles/networkconnectivity.hubAdmin` grants 54 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 52 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkconnectivity.hubAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
