# `roles/pubsub.editor`

Modify topics and subscriptions, publish and consume messages.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsub.editor` |
| Title | Pub/Sub Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 59 |
| Service | [pubsub](../overview.md) |

## Permissions

`roles/pubsub.editor` grants 59 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [pubsub](permissions/pubsub/overview.md) | 43 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsub.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
