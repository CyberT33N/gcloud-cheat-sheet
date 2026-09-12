# `roles/vmmigration.admin`

Ability to view and edit all VM Migration objects

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmmigration.admin` |
| Title | VM Migration Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 70 |
| Service | [vmmigration](../overview.md) |

## Permissions

`roles/vmmigration.admin` grants 70 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vmmigration](permissions/vmmigration/overview.md) | 63 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmmigration.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
