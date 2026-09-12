# `roles/gdchardwaremanagement.operator`

Create, read, and update access to GDC Hardware Management resources that support those operations. Also grants delete access to HardwareGroup resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gdchardwaremanagement.operator` |
| Title | GDC Hardware Management Operator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 36 |
| Service | [gdchardwaremanagement](../overview.md) |

## Permissions

`roles/gdchardwaremanagement.operator` grants 36 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gdchardwaremanagement](permissions/gdchardwaremanagement/overview.md) | 34 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gdchardwaremanagement.operator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
