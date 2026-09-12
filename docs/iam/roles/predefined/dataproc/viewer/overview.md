# `roles/dataproc.viewer`

Read-only access to Dataproc resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.viewer` |
| Title | Dataproc Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.viewer` grants 27 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 5 |
| [dataproc](permissions/dataproc/overview.md) | 20 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
