# `roles/servicemanagement.admin`

Full control of Google Service Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicemanagement.admin` |
| Title | Service Management Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 34 |
| Service | [servicemanagement](../overview.md) |

## Permissions

`roles/servicemanagement.admin` grants 34 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |
| [serviceconsumermanagement](permissions/serviceconsumermanagement/overview.md) | 8 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 11 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicemanagement.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
