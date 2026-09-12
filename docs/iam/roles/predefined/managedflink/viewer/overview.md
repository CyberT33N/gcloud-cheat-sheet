# `roles/managedflink.viewer`

Readonly access to Managed Flink resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedflink.viewer` |
| Title | Managed Flink Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [managedflink](../overview.md) |

## Permissions

`roles/managedflink.viewer` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [managedflink](permissions/managedflink/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedflink.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
