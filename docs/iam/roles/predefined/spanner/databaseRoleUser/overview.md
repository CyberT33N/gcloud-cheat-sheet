# `roles/spanner.databaseRoleUser`

In conjunction with the IAM role Cloud Spanner Fine-grained Access User, grants permissions to individual Spanner database roles. Add a condition for each desired Spanner database role that includes the resource type of `spanner.googleapis.com/DatabaseRole` and the resource name ending with `/<your Spanner database role>`.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.databaseRoleUser` |
| Title | Cloud Spanner Database Role User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 0 |
| Service | [spanner](../overview.md) |

## Permissions

The IAM API (`view=FULL`) returns no included permissions for this role.

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.databaseRoleUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
