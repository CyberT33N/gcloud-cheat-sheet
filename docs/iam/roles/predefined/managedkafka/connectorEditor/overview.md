# `roles/managedkafka.connectorEditor`

Provides read and write access to connectors. Intended for, e.g., developers who configure and operate connectors.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.connectorEditor` |
| Title | Managed Kafka Connector Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 52 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.connectorEditor` grants 52 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [managedkafka](permissions/managedkafka/overview.md) | 39 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.connectorEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
