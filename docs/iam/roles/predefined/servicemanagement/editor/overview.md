# `roles/servicemanagement.editor`

Editor role for Service Management.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicemanagement.editor` |
| Title | Service Management Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [servicemanagement](../overview.md) |

## Permissions

`roles/servicemanagement.editor` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicemanagement.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
