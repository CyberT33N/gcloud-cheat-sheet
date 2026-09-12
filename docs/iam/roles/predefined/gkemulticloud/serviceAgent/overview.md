# `roles/gkemulticloud.serviceAgent`

Grants the Anthos Multi-Cloud Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkemulticloud.serviceAgent` |
| Title | Anthos Multi-Cloud Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 62 |
| Service | [gkemulticloud](../overview.md) |

## Permissions

`roles/gkemulticloud.serviceAgent` grants 62 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 55 |
| [gkemulticloud](permissions/gkemulticloud/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkemulticloud.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
