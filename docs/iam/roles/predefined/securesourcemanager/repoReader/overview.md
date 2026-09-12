# `roles/securesourcemanager.repoReader`

A repoReader has read access to a particular repository, including its child components. They cannot create repositories, and do not manage IAM policies on the repository.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.repoReader` |
| Title | Secure Source Manager Repository Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.repoReader` grants 20 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 18 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.repoReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
