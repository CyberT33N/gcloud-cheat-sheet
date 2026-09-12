# `roles/firebaseapphosting.serviceAgent`

Gives Firebase App Hosting access to resource for Building & Deploying Backends.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseapphosting.serviceAgent` |
| Title | Firebase App Hosting Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 48 |
| Service | [firebaseapphosting](../overview.md) |

## Permissions

`roles/firebaseapphosting.serviceAgent` grants 48 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 8 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [developerconnect](permissions/developerconnect/overview.md) | 4 |
| [firebaseapphosting](permissions/firebaseapphosting/overview.md) | 16 |
| [iam](permissions/iam/overview.md) | 1 |
| [run](permissions/run/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseapphosting.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
