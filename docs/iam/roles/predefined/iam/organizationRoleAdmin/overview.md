# `roles/iam.organizationRoleAdmin`

Access to administer all custom roles in the organization and the projects below it.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.organizationRoleAdmin` |
| Title | Organization Role Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.organizationRoleAdmin` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.organizationRoleAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
