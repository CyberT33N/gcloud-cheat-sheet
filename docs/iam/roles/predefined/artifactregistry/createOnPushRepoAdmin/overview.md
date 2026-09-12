# `roles/artifactregistry.createOnPushRepoAdmin`

Access to manage artifacts in repositories, as well as create new repositories on push

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.createOnPushRepoAdmin` |
| Title | Artifact Registry Create-on-Push Repository Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 54 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.createOnPushRepoAdmin` grants 54 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 53 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.createOnPushRepoAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
