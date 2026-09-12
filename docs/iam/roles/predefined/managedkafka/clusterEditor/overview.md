# `roles/managedkafka.clusterEditor`

Provides read and write access to Kafka clusters. Intended for, e.g., IT Departments that provision Kafka clusters, but need not be able to read or modify topics or consumer groups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.clusterEditor` |
| Title | Managed Kafka Cluster Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 48 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.clusterEditor` grants 48 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [managedkafka](permissions/managedkafka/overview.md) | 35 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.clusterEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
