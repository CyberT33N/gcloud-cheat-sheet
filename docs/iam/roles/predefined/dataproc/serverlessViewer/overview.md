# `roles/dataproc.serverlessViewer`

Permissions needed to view serverless sessions and batches

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.serverlessViewer` |
| Title | Dataproc Serverless Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.serverlessViewer` grants 13 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 5 |
| [dataproc](permissions/dataproc/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.serverlessViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
