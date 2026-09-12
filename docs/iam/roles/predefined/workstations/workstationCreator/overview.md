# `roles/workstations.workstationCreator`

Grants ability to create Workstation resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.workstationCreator` |
| Title | Cloud Workstations Creator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.workstationCreator` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workstations](permissions/workstations/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.workstationCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
