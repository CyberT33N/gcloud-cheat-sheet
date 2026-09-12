# `roles/pubsub.serviceAgent`

Grants Cloud Pub/Sub Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsub.serviceAgent` |
| Title | Cloud Pub/Sub Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [pubsub](../overview.md) |

## Permissions

`roles/pubsub.serviceAgent` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsub.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
