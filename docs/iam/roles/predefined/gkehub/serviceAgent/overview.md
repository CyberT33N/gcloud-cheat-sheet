# `roles/gkehub.serviceAgent`

Gives the GKE Hub service agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.serviceAgent` |
| Title | GKE Hub Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 80 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.serviceAgent` grants 80 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 28 |
| [gkehub](permissions/gkehub/overview.md) | 18 |
| [gkemulticloud](permissions/gkemulticloud/overview.md) | 2 |
| [gkeonprem](permissions/gkeonprem/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 18 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
