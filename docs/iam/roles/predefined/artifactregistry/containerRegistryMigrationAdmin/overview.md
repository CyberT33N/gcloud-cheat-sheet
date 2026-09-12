# `roles/artifactregistry.containerRegistryMigrationAdmin`

Access to run migration tooling to migrate from Container Registry to Artifact Registry

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.containerRegistryMigrationAdmin` |
| Title | Container Registry -> Artifact Registry Migration Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.containerRegistryMigrationAdmin` grants 18 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 9 |
| [cloudasset](permissions/cloudasset/overview.md) | 3 |
| [iam](permissions/iam/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.containerRegistryMigrationAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
