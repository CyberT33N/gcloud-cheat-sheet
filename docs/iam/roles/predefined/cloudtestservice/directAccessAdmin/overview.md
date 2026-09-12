# `roles/cloudtestservice.directAccessAdmin`

Administrator owning access to Direct Access

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtestservice.directAccessAdmin` |
| Title | Firebase Test Lab Direct Access Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 14 |
| Service | [cloudtestservice](../overview.md) |

## Permissions

`roles/cloudtestservice.directAccessAdmin` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 7 |
| [devicestreaming](permissions/devicestreaming/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtestservice.directAccessAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
