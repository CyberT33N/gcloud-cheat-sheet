# `roles/iam.denyAdmin`

Deny admin role, with permissions to read and modify deny policies

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.denyAdmin` |
| Title | Deny Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.denyAdmin` grants 11 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 5 |
| [policyanalyzer](permissions/policyanalyzer/overview.md) | 1 |
| [policysimulator](permissions/policysimulator/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.denyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
