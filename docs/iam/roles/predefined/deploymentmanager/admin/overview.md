# `roles/deploymentmanager.admin`

Admin role for Deployment Manager.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/deploymentmanager.admin` |
| Title | Deployment Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 44 |
| Service | [deploymentmanager](../overview.md) |

## Permissions

`roles/deploymentmanager.admin` grants 44 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 32 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/deploymentmanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
