# `roles/workloadidentity.admin`

Full access to Workload Identity API resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadidentity.admin` |
| Title | Workload Identity API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [workloadidentity](../overview.md) |

## Permissions

`roles/workloadidentity.admin` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workloadidentity](permissions/workloadidentity/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadidentity.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
