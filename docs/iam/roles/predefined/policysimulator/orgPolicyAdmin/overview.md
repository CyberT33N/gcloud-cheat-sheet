# `roles/policysimulator.orgPolicyAdmin`

OrgPolicy Admin that can run and access simulations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/policysimulator.orgPolicyAdmin` |
| Title | OrgPolicy Simulator Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [policysimulator](../overview.md) |

## Permissions

`roles/policysimulator.orgPolicyAdmin` grants 13 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 4 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 4 |
| [policysimulator](permissions/policysimulator/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/policysimulator.orgPolicyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
