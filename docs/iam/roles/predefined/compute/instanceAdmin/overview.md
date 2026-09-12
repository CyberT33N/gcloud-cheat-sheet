# `roles/compute.instanceAdmin`

Full control of Compute Engine instance resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.instanceAdmin` |
| Title | Compute Instance Admin (beta) |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 276 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.instanceAdmin` grants 276 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 238 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.instanceAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
