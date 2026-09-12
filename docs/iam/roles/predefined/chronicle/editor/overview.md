# `roles/chronicle.editor`

Modify Access to Chronicle API resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.editor` |
| Title | Chronicle API Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 522 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.editor` grants 522 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 520 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
