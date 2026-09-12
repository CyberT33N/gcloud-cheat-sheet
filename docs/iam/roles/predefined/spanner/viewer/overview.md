# `roles/spanner.viewer`

Viewer access to Cloud Spanner resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.viewer` |
| Title | Cloud Spanner Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.viewer` grants 13 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [spanner](permissions/spanner/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
