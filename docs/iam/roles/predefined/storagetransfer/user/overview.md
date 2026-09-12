# `roles/storagetransfer.user`

Create and update storage transfer jobs and operations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storagetransfer.user` |
| Title | Storage Transfer User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [storagetransfer](../overview.md) |

## Permissions

`roles/storagetransfer.user` grants 20 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storagetransfer](permissions/storagetransfer/overview.md) | 18 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storagetransfer.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
