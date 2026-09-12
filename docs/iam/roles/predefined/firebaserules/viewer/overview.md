# `roles/firebaserules.viewer`

Read-only access on all resources with the ability to test Rulesets.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaserules.viewer` |
| Title | Firebase Rules Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [firebaserules](../overview.md) |

## Permissions

`roles/firebaserules.viewer` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebaserules](permissions/firebaserules/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaserules.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
