# `roles/securitycenter.settingsAdmin`

Admin(super user) access to security center settings

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.settingsAdmin` |
| Title | Security Center Settings Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 93 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.settingsAdmin` grants 93 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |
| [securitycenter](permissions/securitycenter/overview.md) | 51 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 37 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.settingsAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
