# `roles/securesourcemanager.instanceManager`

Read-write access to all Secure Source Manager resources (full control except for the ability to modify permissions).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.instanceManager` |
| Title | Secure Source Manager Instance Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.instanceManager` grants 20 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 18 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.instanceManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
