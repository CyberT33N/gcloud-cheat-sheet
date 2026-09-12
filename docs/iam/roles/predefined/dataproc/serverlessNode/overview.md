# `roles/dataproc.serverlessNode`

Node access to Dataproc Serverless sessions and batches. Intended for service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.serverlessNode` |
| Title | Dataproc Serverless Node. |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.serverlessNode` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataproc](permissions/dataproc/overview.md) | 4 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.serverlessNode --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
