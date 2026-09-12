# `roles/iam.principalAccessBoundaryUser`

Principal Access Boundary Policies user role, with permissions to view principal access boundary policies, and to bind and unbind principal access boundary policies to targets

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.principalAccessBoundaryUser` |
| Title | Principal Access Boundary Policy User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.principalAccessBoundaryUser` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.principalAccessBoundaryUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
