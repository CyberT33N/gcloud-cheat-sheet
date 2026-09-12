# `roles/storagetransfer.serviceAgent`

Grants Storage Transfer Service Agent permissions required to run transfers

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storagetransfer.serviceAgent` |
| Title | Storage Transfer Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [storagetransfer](../overview.md) |

## Permissions

`roles/storagetransfer.serviceAgent` grants 11 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storagetransfer.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
