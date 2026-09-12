# `roles/devicestreaming.viewer`

Viewer, able to see what device streaming sessions exist

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/devicestreaming.viewer` |
| Title | Device Streaming Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [devicestreaming](../overview.md) |

## Permissions

`roles/devicestreaming.viewer` grants 5 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 1 |
| [devicestreaming](permissions/devicestreaming/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/devicestreaming.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
