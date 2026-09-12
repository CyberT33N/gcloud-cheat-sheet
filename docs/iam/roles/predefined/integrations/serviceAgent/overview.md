# `roles/integrations.serviceAgent`

Service agent that grants access to execute an integration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/integrations.serviceAgent` |
| Title | Application Integration Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 144 |
| Service | [integrations](../overview.md) |

## Permissions

`roles/integrations.serviceAgent` grants 144 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 1 |
| [cloudscheduler](permissions/cloudscheduler/overview.md) | 10 |
| [connectors](permissions/connectors/overview.md) | 12 |
| [iam](permissions/iam/overview.md) | 2 |
| [integrations](permissions/integrations/overview.md) | 69 |
| [pubsub](permissions/pubsub/overview.md) | 28 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/integrations.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
