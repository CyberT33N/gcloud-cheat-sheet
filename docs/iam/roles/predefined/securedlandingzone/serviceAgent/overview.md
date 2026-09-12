# `roles/securedlandingzone.serviceAgent`

Grants Secured Landing Zone service account permissions to manage resources in the customer project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securedlandingzone.serviceAgent` |
| Title | Secured Landing Zone Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 22 |
| Service | [securedlandingzone](../overview.md) |

## Permissions

`roles/securedlandingzone.serviceAgent` grants 22 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 5 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securedlandingzone.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
