# `roles/artifactregistry.repoAdmin`

Access to manage artifacts in repositories.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.repoAdmin` |
| Title | Artifact Registry Repository Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 53 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.repoAdmin` grants 53 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 52 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.repoAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
