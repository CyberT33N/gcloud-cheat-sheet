# `roles/servicemanagement.configEditor`

Access to update the service config and create rollouts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicemanagement.configEditor` |
| Title | Service Config Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [servicemanagement](../overview.md) |

## Permissions

`roles/servicemanagement.configEditor` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [servicemanagement](permissions/servicemanagement/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicemanagement.configEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
