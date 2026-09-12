# `roles/confidentialcomputing.workloadUser`

Grants the ability to generate an attestation token and run a workload in a VM. Intended for service accounts that run on Confidential Space VMs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/confidentialcomputing.workloadUser` |
| Title | Confidential Space Workload User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [confidentialcomputing](../overview.md) |

## Permissions

`roles/confidentialcomputing.workloadUser` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [confidentialcomputing](permissions/confidentialcomputing/overview.md) | 4 |
| [logging](permissions/logging/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/confidentialcomputing.workloadUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
