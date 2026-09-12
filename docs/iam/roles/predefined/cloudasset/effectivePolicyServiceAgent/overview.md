# `roles/cloudasset.effectivePolicyServiceAgent`

Give effective policy service account access to search all resources and IAM policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudasset.effectivePolicyServiceAgent` |
| Title | Effective Policies Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [cloudasset](../overview.md) |

## Permissions

`roles/cloudasset.effectivePolicyServiceAgent` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudasset.effectivePolicyServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
