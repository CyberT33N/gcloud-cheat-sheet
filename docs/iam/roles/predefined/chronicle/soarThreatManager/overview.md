# `roles/chronicle.soarThreatManager`

Grants threat manager access to Chronicle SOAR.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.soarThreatManager` |
| Title | Chronicle SOAR Threat Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 39 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.soarThreatManager` grants 39 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 15 |
| [cloudasset](permissions/cloudasset/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.soarThreatManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
