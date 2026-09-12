# `roles/artifactregistry.admin`

Administrator access to create and manage repositories.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/artifactregistry.admin` |
| Title | Artifact Registry Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 67 |
| Service | [artifactregistry](../overview.md) |

## Permissions

`roles/artifactregistry.admin` grants 67 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 61 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/artifactregistry.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
