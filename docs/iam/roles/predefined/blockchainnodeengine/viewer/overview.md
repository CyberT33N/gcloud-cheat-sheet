# `roles/blockchainnodeengine.viewer`

Readonly access to Blockchain Node Engine resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/blockchainnodeengine.viewer` |
| Title | Blockchain Node Engine Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [blockchainnodeengine](../overview.md) |

## Permissions

`roles/blockchainnodeengine.viewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [blockchainnodeengine](permissions/blockchainnodeengine/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/blockchainnodeengine.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
