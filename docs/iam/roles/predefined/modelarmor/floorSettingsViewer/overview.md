# `roles/modelarmor.floorSettingsViewer`

Grants read access to all Model Armor Floor Setting resources. Intended for viewers.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/modelarmor.floorSettingsViewer` |
| Title | Model Armor Floor Setting Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [modelarmor](../overview.md) |

## Permissions

`roles/modelarmor.floorSettingsViewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [modelarmor](permissions/modelarmor/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/modelarmor.floorSettingsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
