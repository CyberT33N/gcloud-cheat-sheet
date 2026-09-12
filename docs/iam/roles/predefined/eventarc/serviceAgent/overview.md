# `roles/eventarc.serviceAgent`

Gives Eventarc service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/eventarc.serviceAgent` |
| Title | Eventarc Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 44 |
| Service | [eventarc](../overview.md) |

## Permissions

`roles/eventarc.serviceAgent` grants 44 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 4 |
| [container](permissions/container/overview.md) | 14 |
| [dns](permissions/dns/overview.md) | 1 |
| [eventarc](permissions/eventarc/overview.md) | 3 |
| [iam](permissions/iam/overview.md) | 3 |
| [pubsub](permissions/pubsub/overview.md) | 13 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 2 |
| [workflows](permissions/workflows/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/eventarc.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
