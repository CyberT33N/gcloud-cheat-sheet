# `roles/managedflink.serviceAgent`

Gives Managed Flink Service Agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedflink.serviceAgent` |
| Title | Managed Flink Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [managedflink](../overview.md) |

## Permissions

`roles/managedflink.serviceAgent` grants 23 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 11 |
| [dns](permissions/dns/overview.md) | 1 |
| [managedkafka](permissions/managedkafka/overview.md) | 3 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedflink.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
