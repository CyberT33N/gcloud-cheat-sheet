# `roles/enterprisepurchasing.viewer`

Readonly access to Enterprise Purchasing resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/enterprisepurchasing.viewer` |
| Title | Enterprise Purchasing Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [enterprisepurchasing](../overview.md) |

## Permissions

`roles/enterprisepurchasing.viewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [enterprisepurchasing](permissions/enterprisepurchasing/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/enterprisepurchasing.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
