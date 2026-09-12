# `roles/appengineflex.serviceAgent`

Can edit and manage App Engine Flexible Environment apps. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengineflex.serviceAgent` |
| Title | App Engine flexible environment Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 169 |
| Service | [appengineflex](../overview.md) |

## Permissions

`roles/appengineflex.serviceAgent` grants 169 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 5 |
| [billing](permissions/billing/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 123 |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 12 |
| [iam](permissions/iam/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengineflex.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
