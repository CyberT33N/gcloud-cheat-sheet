# `roles/chronicle.soarAdmin`

Grants admin access to Chronicle SOAR.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.soarAdmin` |
| Title | Chronicle SOAR Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 293 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.soarAdmin` grants 293 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 269 |
| [cloudasset](permissions/cloudasset/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.soarAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
