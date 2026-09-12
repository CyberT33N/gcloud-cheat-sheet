# `roles/cloudtestservice.directAccessViewer`

Viewer, able to see what direct access sessions exist

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtestservice.directAccessViewer` |
| Title | Firebase Test Lab Direct Access Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [cloudtestservice](../overview.md) |

## Permissions

`roles/cloudtestservice.directAccessViewer` grants 7 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 3 |
| [devicestreaming](permissions/devicestreaming/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtestservice.directAccessViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
