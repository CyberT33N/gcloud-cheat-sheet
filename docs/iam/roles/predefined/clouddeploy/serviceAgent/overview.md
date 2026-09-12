# `roles/clouddeploy.serviceAgent`

Gives Cloud Deploy Service Account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddeploy.serviceAgent` |
| Title | Cloud Deploy Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [clouddeploy](../overview.md) |

## Permissions

`roles/clouddeploy.serviceAgent` grants 15 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 5 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddeploy.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
