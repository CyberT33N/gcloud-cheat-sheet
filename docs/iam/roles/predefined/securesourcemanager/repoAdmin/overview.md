# `roles/securesourcemanager.repoAdmin`

A repoAdmin has the ability to CRUD a repository and its children as well as assign users to a repository. They can also set, get, or check IAM policies on the repository.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.repoAdmin` |
| Title | Secure Source Manager Repository Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 53 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.repoAdmin` grants 53 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 51 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.repoAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
