# `roles/nestconsole.homeDeveloperAdmin`

Admin access to Google Home Developer Console resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/nestconsole.homeDeveloperAdmin` |
| Title | Google Home Developer Console Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [nestconsole](../overview.md) |

## Permissions

`roles/nestconsole.homeDeveloperAdmin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [nestconsole](permissions/nestconsole/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/nestconsole.homeDeveloperAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
