# `roles/deploymentmanager.typeEditor`

Read and Write access to all Type Registry resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/deploymentmanager.typeEditor` |
| Title | Deployment Manager Type Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [deploymentmanager](../overview.md) |

## Permissions

`roles/deploymentmanager.typeEditor` grants 29 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 18 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/deploymentmanager.typeEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
