# `roles/compute.storageAdmin`

Full control of Compute Engine storage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.storageAdmin` |
| Title | Compute Storage Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 160 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.storageAdmin` grants 160 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 7 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 136 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.storageAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
