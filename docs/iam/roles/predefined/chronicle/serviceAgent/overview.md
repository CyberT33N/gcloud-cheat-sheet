# `roles/chronicle.serviceAgent`

Grants Chronicle global data access to customer project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.serviceAgent` |
| Title | Chronicle Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 92 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.serviceAgent` grants 92 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 17 |
| [chronicle](permissions/chronicle/overview.md) | 47 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 2 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [mcp](permissions/mcp/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 6 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
