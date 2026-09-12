# `roles/storagetransfer.viewer`

Read access to storage transfer jobs and operations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storagetransfer.viewer` |
| Title | Storage Transfer Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [storagetransfer](../overview.md) |

## Permissions

`roles/storagetransfer.viewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storagetransfer](permissions/storagetransfer/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storagetransfer.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
