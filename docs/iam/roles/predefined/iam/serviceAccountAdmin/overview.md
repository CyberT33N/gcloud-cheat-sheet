# `roles/iam.serviceAccountAdmin`

Create and manage service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.serviceAccountAdmin` |
| Title | Service Account Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.serviceAccountAdmin` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.serviceAccountAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
