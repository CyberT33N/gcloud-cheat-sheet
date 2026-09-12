# `roles/orgpolicy.policyAdmin`

The permission to set Organization Policies on resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/orgpolicy.policyAdmin` |
| Title | Organization Policy Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 26 |
| Service | [orgpolicy](../overview.md) |

## Permissions

`roles/orgpolicy.policyAdmin` grants 26 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 4 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 12 |
| [policysimulator](permissions/policysimulator/overview.md) | 4 |
| [recommender](permissions/recommender/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/orgpolicy.policyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
