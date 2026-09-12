# `roles/securitycentermanagement.settingsViewer`

Readonly access to Cloud Security Command Center settings

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycentermanagement.settingsViewer` |
| Title | Security Center Management Settings Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [securitycentermanagement](../overview.md) |

## Permissions

`roles/securitycentermanagement.settingsViewer` grants 24 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 2 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 19 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycentermanagement.settingsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
