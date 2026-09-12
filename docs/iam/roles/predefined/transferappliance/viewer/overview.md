# `roles/transferappliance.viewer`

Read-only access to Transfer Appliance all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/transferappliance.viewer` |
| Title | Transfer Appliance Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [transferappliance](../overview.md) |

## Permissions

`roles/transferappliance.viewer` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [transferappliance](permissions/transferappliance/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/transferappliance.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
