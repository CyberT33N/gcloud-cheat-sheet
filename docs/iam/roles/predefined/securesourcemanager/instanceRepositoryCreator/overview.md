# `roles/securesourcemanager.instanceRepositoryCreator`

An instance repository creator can connect to a Cloud Git instance via IAP (HTTPS) and create repositories in the instance.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.instanceRepositoryCreator` |
| Title | Secure Source Manager Instance Repository Creator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.instanceRepositoryCreator` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.instanceRepositoryCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
