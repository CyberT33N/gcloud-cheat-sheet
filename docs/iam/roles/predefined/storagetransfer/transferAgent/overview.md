# `roles/storagetransfer.transferAgent`

Perform transfers from an agent.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storagetransfer.transferAgent` |
| Title | Storage Transfer Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [storagetransfer](../overview.md) |

## Permissions

`roles/storagetransfer.transferAgent` grants 15 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 9 |
| [storagetransfer](permissions/storagetransfer/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storagetransfer.transferAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
