# `roles/workstations.policyAdmin`

Grants permission to set IAM policy on workstation.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.policyAdmin` |
| Title | Cloud Workstations Policy Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.policyAdmin` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [workstations](permissions/workstations/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.policyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
