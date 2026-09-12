# `roles/speakerid.viewer`

Grants read access to all Speaker ID resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/speakerid.viewer` |
| Title | Speaker ID Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [speakerid](../overview.md) |

## Permissions

`roles/speakerid.viewer` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [speakerid](permissions/speakerid/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/speakerid.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
