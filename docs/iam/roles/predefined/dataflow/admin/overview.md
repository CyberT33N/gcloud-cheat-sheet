# `roles/dataflow.admin`

Minimal role for creating and managing dataflow jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataflow.admin` |
| Title | Dataflow Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 38 |
| Service | [dataflow](../overview.md) |

## Permissions

`roles/dataflow.admin` grants 38 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 4 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [recommender](permissions/recommender/overview.md) | 3 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataflow.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
