# `roles/artifactregistry.reader`

Access to read repository items.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.reader` |
| Title | Artifact Registry Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.reader` grants 33 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
