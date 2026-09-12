# `roles/spanner.serviceAgent`

Cloud Spanner API Service Agent

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.serviceAgent` |
| Title | Cloud Spanner API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 38 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.serviceAgent` grants 38 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 16 |
| [logging](permissions/logging/overview.md) | 1 |
| [run](permissions/run/overview.md) | 2 |
| [spanner](permissions/spanner/overview.md) | 7 |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
