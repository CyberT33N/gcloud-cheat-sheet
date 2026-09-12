# `roles/dataproc.hubAgent`

Allows management of Dataproc resources. Intended for service accounts running Dataproc Hub instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.hubAgent` |
| Title | Dataproc Hub Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 55 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.hubAgent` grants 55 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 5 |
| [dataproc](permissions/dataproc/overview.md) | 13 |
| [iam](permissions/iam/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 28 |
| [observability](permissions/observability/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.hubAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
