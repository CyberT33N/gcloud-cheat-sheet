# `roles/publicca.externalAccountKeyCreator`

This role can create a new externalAccountKey resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/publicca.externalAccountKeyCreator` |
| Title | External Account Key Creator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [publicca](../overview.md) |

## Permissions

`roles/publicca.externalAccountKeyCreator` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [publicca](permissions/publicca/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/publicca.externalAccountKeyCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
