# `roles/securitycentermanagement.viewer`

Readonly access to Cloud Security Command Center services and custom modules configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycentermanagement.viewer` |
| Title | Security Center Management Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [securitycentermanagement](../overview.md) |

## Permissions

`roles/securitycentermanagement.viewer` grants 27 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 2 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycentermanagement.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
