# `roles/workloadmanager.admin`

Full access to Workload Manager all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadmanager.admin` |
| Title | Workload Manager Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 60 |
| Service | [workloadmanager](../overview.md) |

## Permissions

`roles/workloadmanager.admin` grants 60 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 8 |
| [dns](permissions/dns/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [storage](permissions/storage/overview.md) | 2 |
| [workloadmanager](permissions/workloadmanager/overview.md) | 34 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadmanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
