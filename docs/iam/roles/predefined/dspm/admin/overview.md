# `roles/dspm.admin`

Full access to Data Security Posture Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dspm.admin` |
| Title | Data Security Posture Management Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [dspm](../overview.md) |

## Permissions

`roles/dspm.admin` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dspm](permissions/dspm/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dspm.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
