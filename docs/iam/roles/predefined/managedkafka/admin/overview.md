# `roles/managedkafka.admin`

Full access to Managed Kafka resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.admin` |
| Title | Managed Kafka Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 80 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.admin` grants 80 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [managedkafka](permissions/managedkafka/overview.md) | 67 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
