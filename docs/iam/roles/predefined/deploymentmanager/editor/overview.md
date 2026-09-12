# `roles/deploymentmanager.editor`

Read and Write access to all Deployment Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/deploymentmanager.editor` |
| Title | Deployment Manager Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [deploymentmanager](../overview.md) |

## Permissions

`roles/deploymentmanager.editor` grants 42 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 30 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/deploymentmanager.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
