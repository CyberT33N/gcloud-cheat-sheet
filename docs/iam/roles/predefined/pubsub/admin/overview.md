# `roles/pubsub.admin`

Full access to topics, subscriptions, and snapshots.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsub.admin` |
| Title | Pub/Sub Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 67 |
| Service | [pubsub](../overview.md) |

## Permissions

`roles/pubsub.admin` grants 67 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [pubsub](permissions/pubsub/overview.md) | 51 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsub.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
