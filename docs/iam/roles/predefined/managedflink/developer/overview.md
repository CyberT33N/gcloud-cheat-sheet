# `roles/managedflink.developer`

Full access to Managed Flink Jobs and Sessions and read access to Deployments.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedflink.developer` |
| Title | Managed Flink Developer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 18 |
| Service | [managedflink](../overview.md) |

## Permissions

`roles/managedflink.developer` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [managedflink](permissions/managedflink/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedflink.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
