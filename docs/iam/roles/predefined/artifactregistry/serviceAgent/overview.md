# `roles/artifactregistry.serviceAgent`

Gives the Artifact Registry service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.serviceAgent` |
| Title | Artifact Registry Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.serviceAgent` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 4 |
| [pubsub](permissions/pubsub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
