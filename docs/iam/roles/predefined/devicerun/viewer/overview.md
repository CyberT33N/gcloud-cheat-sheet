# `roles/devicerun.viewer`

Readonly access to Device Run resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/devicerun.viewer` |
| Title | Device Run Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [devicerun](../overview.md) |

## Permissions

`roles/devicerun.viewer` grants 13 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 1 |
| [devicerun](permissions/devicerun/overview.md) | 8 |
| [devicestreaming](permissions/devicestreaming/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/devicerun.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
