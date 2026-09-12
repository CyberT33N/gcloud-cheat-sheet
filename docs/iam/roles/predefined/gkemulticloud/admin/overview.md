# `roles/gkemulticloud.admin`

Admin access to Anthos Multi-cloud resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkemulticloud.admin` |
| Title | Anthos Multi-cloud Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [gkemulticloud](../overview.md) |

## Permissions

`roles/gkemulticloud.admin` grants 49 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkemulticloud](permissions/gkemulticloud/overview.md) | 47 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkemulticloud.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
