# `roles/managedkafka.connectClusterEditor`

Provides read and write access to Kafka Connect clusters. Intended for, e.g., IT Departments that provision Kafka Connect clusters, but need not be able to read or modify connectors.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.connectClusterEditor` |
| Title | Managed Kafka Connect Cluster Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.connectClusterEditor` grants 7 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [managedkafka](permissions/managedkafka/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.connectClusterEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
