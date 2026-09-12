# `roles/managedkafka.serviceAgent`

Gives Managed Kafka Service Agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedkafka.serviceAgent` |
| Title | Managed Kafka Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 36 |
| Service | [managedkafka](../overview.md) |

## Permissions

`roles/managedkafka.serviceAgent` grants 36 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 21 |
| [dns](permissions/dns/overview.md) | 10 |
| [managedkafka](permissions/managedkafka/overview.md) | 1 |
| [privateca](permissions/privateca/overview.md) | 1 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedkafka.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
