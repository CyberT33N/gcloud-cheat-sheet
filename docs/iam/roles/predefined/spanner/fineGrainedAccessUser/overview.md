# `roles/spanner.fineGrainedAccessUser`

Grants permissions to use Spanner's fine-grained access control framework. To grant access to specific database roles, also add the Cloud Spanner Database Role User IAM role and its necessary conditions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.fineGrainedAccessUser` |
| Title | Cloud Spanner Fine-grained Access User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.fineGrainedAccessUser` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [spanner](permissions/spanner/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.fineGrainedAccessUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
