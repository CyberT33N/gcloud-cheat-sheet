# `roles/config.admin`

Full access to Cloud Infrastructure Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/config.admin` |
| Title | Cloud Infrastructure Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 50 |
| Service | [config](../overview.md) |

## Permissions

`roles/config.admin` grants 50 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [config](permissions/config/overview.md) | 48 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/config.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
