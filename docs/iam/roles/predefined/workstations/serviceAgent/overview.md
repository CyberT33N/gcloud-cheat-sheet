# `roles/workstations.serviceAgent`

Grants the Workstations Service Account access to manage resources in consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.serviceAgent` |
| Title | Workstations Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 75 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.serviceAgent` grants 75 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 63 |
| [dns](permissions/dns/overview.md) | 2 |
| [iam](permissions/iam/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
