# `roles/clouddeploy.jobRunner`

Permission to execute Cloud Deploy work without permission to deliver to a target.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddeploy.jobRunner` |
| Title | Cloud Deploy Runner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [clouddeploy](../overview.md) |

## Permissions

`roles/clouddeploy.jobRunner` grants 5 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clouddeploy](permissions/clouddeploy/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddeploy.jobRunner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
