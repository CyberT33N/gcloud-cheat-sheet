# `roles/genomics.serviceAgent`

Gives Genomics Service Account access to compute resources. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/genomics.serviceAgent` |
| Title | Genomics Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 524 |
| Service | [genomics](../overview.md) |

## Permissions

`roles/genomics.serviceAgent` grants 524 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [compute](permissions/compute/overview.md) | 488 |
| [iam](permissions/iam/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/genomics.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
