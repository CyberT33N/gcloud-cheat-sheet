# `roles/securitycentermanagement.customModulesViewer`

Readonly access to Cloud Security Command Center custom modules.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycentermanagement.customModulesViewer` |
| Title | Security Center Management Custom Modules Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [securitycentermanagement](../overview.md) |

## Permissions

`roles/securitycentermanagement.customModulesViewer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycentermanagement.customModulesViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
