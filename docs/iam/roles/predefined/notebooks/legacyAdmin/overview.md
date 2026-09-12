# `roles/notebooks.legacyAdmin`

Full access to Notebooks all resources through compute API.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.legacyAdmin` |
| Title | Notebooks Legacy Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1161 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.legacyAdmin` grants 1161 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 1062 |
| [notebooks](permissions/notebooks/overview.md) | 61 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.legacyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
