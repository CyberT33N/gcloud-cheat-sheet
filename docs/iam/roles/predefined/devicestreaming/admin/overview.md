# `roles/devicestreaming.admin`

Administrator owning access to Direct Access

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/devicestreaming.admin` |
| Title | Device Streaming Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [devicestreaming](../overview.md) |

## Permissions

`roles/devicestreaming.admin` grants 8 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 1 |
| [devicestreaming](permissions/devicestreaming/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/devicestreaming.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
