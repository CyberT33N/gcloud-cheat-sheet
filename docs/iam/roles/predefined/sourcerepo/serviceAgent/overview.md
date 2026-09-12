# `roles/sourcerepo.serviceAgent`

Allow Cloud Source Repositories to integrate with other Cloud services.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/sourcerepo.serviceAgent` |
| Title | Cloud Source Repositories Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [sourcerepo](../overview.md) |

## Permissions

`roles/sourcerepo.serviceAgent` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/sourcerepo.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
