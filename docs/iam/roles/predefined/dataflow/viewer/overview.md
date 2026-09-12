# `roles/dataflow.viewer`

Read only access to Dataflow jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataflow.viewer` |
| Title | Dataflow Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [dataflow](../overview.md) |

## Permissions

`roles/dataflow.viewer` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataflow](permissions/dataflow/overview.md) | 6 |
| [recommender](permissions/recommender/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataflow.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
