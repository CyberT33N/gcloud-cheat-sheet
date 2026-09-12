# `roles/clouddeploy.developer`

Permission to manage deployment configuration without permission to access operational resources, such as targets.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddeploy.developer` |
| Title | Cloud Deploy Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [clouddeploy](../overview.md) |

## Permissions

`roles/clouddeploy.developer` grants 33 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clouddeploy](permissions/clouddeploy/overview.md) | 31 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddeploy.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
