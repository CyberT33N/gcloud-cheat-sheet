# `roles/source.writer`

Read / Write access to repositories

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/source.writer` |
| Title | Source Repository Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [source](../overview.md) |

## Permissions

`roles/source.writer` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [source](permissions/source/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/source.writer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
