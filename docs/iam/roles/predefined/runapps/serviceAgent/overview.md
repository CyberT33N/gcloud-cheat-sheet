# `roles/runapps.serviceAgent`

Gives Serverless Integrations Service Account access to customer project resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/runapps.serviceAgent` |
| Title | Serverless Integrations Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [runapps](../overview.md) |

## Permissions

`roles/runapps.serviceAgent` grants 41 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 2 |
| [cloudsql](permissions/cloudsql/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 18 |
| [firebasehosting](permissions/firebasehosting/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 1 |
| [redis](permissions/redis/overview.md) | 2 |
| [run](permissions/run/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 7 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/runapps.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
