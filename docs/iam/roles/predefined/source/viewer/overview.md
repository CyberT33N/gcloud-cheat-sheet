# `roles/source.viewer`

Viewer role for source

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/source.viewer` |
| Title | Source Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [source](../overview.md) |

## Permissions

`roles/source.viewer` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [source](permissions/source/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/source.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
