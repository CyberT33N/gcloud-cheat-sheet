# `roles/dataflow.worker`

Worker access to Dataflow.  Intended for service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataflow.worker` |
| Title | Dataflow Worker |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [dataflow](../overview.md) |

## Permissions

`roles/dataflow.worker` grants 23 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 3 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataflow.worker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
