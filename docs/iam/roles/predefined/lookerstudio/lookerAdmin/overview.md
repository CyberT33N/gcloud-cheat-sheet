# `roles/lookerstudio.lookerAdmin`

Admin of Looker instance mapping to a Studio subscription

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/lookerstudio.lookerAdmin` |
| Title | Looker Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 35 |
| Service | [lookerstudio](../overview.md) |

## Permissions

`roles/lookerstudio.lookerAdmin` grants 35 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastudio](permissions/datastudio/overview.md) | 33 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/lookerstudio.lookerAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
