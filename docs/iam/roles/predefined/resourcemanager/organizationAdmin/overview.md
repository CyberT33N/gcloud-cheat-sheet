# `roles/resourcemanager.organizationAdmin`

Access to manage IAM policies and view organization policies for organizations, folders, and projects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/resourcemanager.organizationAdmin` |
| Title | Organization Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 36 |
| Service | [resourcemanager](../overview.md) |

## Permissions

`roles/resourcemanager.organizationAdmin` grants 36 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [essentialcontacts](permissions/essentialcontacts/overview.md) | 6 |
| [iam](permissions/iam/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 25 |

## Inspect this role live

```shell
gcloud iam roles describe roles/resourcemanager.organizationAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
