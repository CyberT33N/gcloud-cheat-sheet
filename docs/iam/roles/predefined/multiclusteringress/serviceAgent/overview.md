# `roles/multiclusteringress.serviceAgent`

Gives the Multi Cluster Ingress service agent access to CloudPlatform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/multiclusteringress.serviceAgent` |
| Title | Multi Cluster Ingress Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 377 |
| Service | [multiclusteringress](../overview.md) |

## Permissions

`roles/multiclusteringress.serviceAgent` grants 377 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [certificatemanager](permissions/certificatemanager/overview.md) | 46 |
| [compute](permissions/compute/overview.md) | 221 |
| [container](permissions/container/overview.md) | 44 |
| [gkehub](permissions/gkehub/overview.md) | 11 |
| [networksecurity](permissions/networksecurity/overview.md) | 13 |
| [networkservices](permissions/networkservices/overview.md) | 32 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/multiclusteringress.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
