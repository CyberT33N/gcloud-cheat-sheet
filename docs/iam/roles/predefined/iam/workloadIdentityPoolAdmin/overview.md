# `roles/iam.workloadIdentityPoolAdmin`

Full rights to create and manage workload identity pools.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.workloadIdentityPoolAdmin` |
| Title | IAM Workload Identity Pool Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 41 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.workloadIdentityPoolAdmin` grants 41 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 4 |
| [iam.googleapis.com](permissions/iam.googleapis.com/overview.md) | 35 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.workloadIdentityPoolAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
