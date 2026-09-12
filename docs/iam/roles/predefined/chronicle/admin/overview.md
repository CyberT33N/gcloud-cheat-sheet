# `roles/chronicle.admin`

Full access to the Chronicle API services, including global settings.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.admin` |
| Title | Chronicle API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 694 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.admin` grants 694 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chronicle](permissions/chronicle/overview.md) | 670 |
| [cloudasset](permissions/cloudasset/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
