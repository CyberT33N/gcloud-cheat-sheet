# `roles/dataflow.developer`

Full operational access to Dataflow jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataflow.developer` |
| Title | Dataflow Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [dataflow](../overview.md) |

## Permissions

`roles/dataflow.developer` grants 33 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 3 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [recommender](permissions/recommender/overview.md) | 3 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataflow.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
