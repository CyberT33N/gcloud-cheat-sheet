# `roles/osconfig.patchJobExecutor`

Access to execute Patch Jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/osconfig.patchJobExecutor` |
| Title | Patch Job Executor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [osconfig](../overview.md) |

## Permissions

`roles/osconfig.patchJobExecutor` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [osconfig](permissions/osconfig/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/osconfig.patchJobExecutor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
