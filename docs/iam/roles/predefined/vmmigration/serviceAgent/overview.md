# `roles/vmmigration.serviceAgent`

Grants VM Migration Service Account access to create migrated VMs, disks and images in the user project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmmigration.serviceAgent` |
| Title | VM Migration Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 40 |
| Service | [vmmigration](../overview.md) |

## Permissions

`roles/vmmigration.serviceAgent` grants 40 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 40 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmmigration.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
