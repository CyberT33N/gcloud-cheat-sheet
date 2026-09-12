# `roles/workstations.admin`

Grants CRUD access to all Workstation resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.admin` |
| Title | Cloud Workstations Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 46 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.admin` grants 46 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 10 |
| [iam](permissions/iam/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workstations](permissions/workstations/overview.md) | 27 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
