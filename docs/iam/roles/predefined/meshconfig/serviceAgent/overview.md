# `roles/meshconfig.serviceAgent`

Apply mesh configuration

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/meshconfig.serviceAgent` |
| Title | Mesh Config Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 95 |
| Service | [meshconfig](../overview.md) |

## Permissions

`roles/meshconfig.serviceAgent` grants 95 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 75 |
| [networksecurity](permissions/networksecurity/overview.md) | 10 |
| [networkservices](permissions/networkservices/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/meshconfig.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
