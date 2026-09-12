# `roles/run.admin`

Full control over all Cloud Run resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/run.admin` |
| Title | Cloud Run Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 97 |
| Service | [run](../overview.md) |

## Permissions

`roles/run.admin` grants 97 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 26 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 69 |

## Inspect this role live

```shell
gcloud iam roles describe roles/run.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
