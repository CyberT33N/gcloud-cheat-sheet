# `roles/dataprocrm.viewer`

Grants read access to all Dataproc Resource Manager resources. Intended for users that need read-only access to Dataproc Resource Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataprocrm.viewer` |
| Title | Dataproc Resource Manager Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [dataprocrm](../overview.md) |

## Permissions

`roles/dataprocrm.viewer` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataprocrm](permissions/dataprocrm/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataprocrm.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
