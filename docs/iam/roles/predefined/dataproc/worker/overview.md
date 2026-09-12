# `roles/dataproc.worker`

Worker access to Dataproc. Intended for service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.worker` |
| Title | Dataproc Worker |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 61 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.worker` grants 61 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudprofiler](permissions/cloudprofiler/overview.md) | 2 |
| [datalineage](permissions/datalineage/overview.md) | 1 |
| [dataproc](permissions/dataproc/overview.md) | 11 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 11 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [storage](permissions/storage/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.worker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
