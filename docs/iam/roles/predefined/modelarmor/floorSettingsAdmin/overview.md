# `roles/modelarmor.floorSettingsAdmin`

Grants full access to all Model Armor Floor Setting resources. Intended for administrators & owners.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/modelarmor.floorSettingsAdmin` |
| Title | Model Armor Floor Setting Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [modelarmor](../overview.md) |

## Permissions

`roles/modelarmor.floorSettingsAdmin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [modelarmor](permissions/modelarmor/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/modelarmor.floorSettingsAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
