# `roles/bigquerymigration.orchestrator`

Orchestrator of EDW migration tasks.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquerymigration.orchestrator` |
| Title | Task Orchestrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [bigquerymigration](../overview.md) |

## Permissions

`roles/bigquerymigration.orchestrator` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquerymigration.orchestrator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
