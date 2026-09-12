# `roles/networkmanagement.viewer`

Read-only access to Network Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networkmanagement.viewer` |
| Title | Network Management Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [networkmanagement](../overview.md) |

## Permissions

`roles/networkmanagement.viewer` grants 24 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networkmanagement](permissions/networkmanagement/overview.md) | 21 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networkmanagement.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
