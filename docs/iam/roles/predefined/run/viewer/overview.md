# `roles/run.viewer`

Can view the state of all Cloud Run resources, including IAM policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/run.viewer` |
| Title | Cloud Run Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 50 |
| Service | [run](../overview.md) |

## Permissions

`roles/run.viewer` grants 50 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 18 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 30 |

## Inspect this role live

```shell
gcloud iam roles describe roles/run.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
