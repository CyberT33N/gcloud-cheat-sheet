# `roles/iam.admin`

Admin role for iam

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.admin` |
| Title | Iam Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 144 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.admin` grants 144 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 54 |
| [iam.googleapis.com](permissions/iam.googleapis.com/overview.md) | 88 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
