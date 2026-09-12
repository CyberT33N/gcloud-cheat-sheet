# `roles/securitycentermanagement.editor`

Editor role for Security Center Management

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycentermanagement.editor` |
| Title | Security Center Management Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [securitycentermanagement](../overview.md) |

## Permissions

`roles/securitycentermanagement.editor` grants 41 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 2 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 36 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycentermanagement.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
