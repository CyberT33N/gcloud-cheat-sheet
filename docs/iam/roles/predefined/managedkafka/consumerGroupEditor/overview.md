# `roles/managedkafka.consumerGroupEditor`

Provides read and write access to consumer group metadata. Intended for, e.g., developers who configure consumer groups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.consumerGroupEditor` |
| Title | Managed Kafka Consumer Group Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 47 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.consumerGroupEditor` grants 47 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [managedkafka](permissions/managedkafka/overview.md) | 34 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.consumerGroupEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
