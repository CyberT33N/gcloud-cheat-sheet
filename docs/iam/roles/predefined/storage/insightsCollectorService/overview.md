# `roles/storage.insightsCollectorService`

Grants read access to object metadata in inventory reports.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.insightsCollectorService` |
| Title | Storage Insights Collector Service |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.insightsCollectorService` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.insightsCollectorService --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
