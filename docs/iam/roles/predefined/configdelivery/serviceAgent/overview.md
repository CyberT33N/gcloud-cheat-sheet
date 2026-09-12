# `roles/configdelivery.serviceAgent`

Gives the Config Delivery service account permission to manage resources 

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/configdelivery.serviceAgent` |
| Title | Config Delivery Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [configdelivery](../overview.md) |

## Permissions

`roles/configdelivery.serviceAgent` grants 42 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 20 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 5 |
| [container](permissions/container/overview.md) | 9 |
| [gkehub](permissions/gkehub/overview.md) | 7 |
| [iam](permissions/iam/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/configdelivery.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
