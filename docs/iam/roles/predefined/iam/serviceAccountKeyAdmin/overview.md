# `roles/iam.serviceAccountKeyAdmin`

Create and manage (and rotate) service account keys.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.serviceAccountKeyAdmin` |
| Title | Service Account Key Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.serviceAccountKeyAdmin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.serviceAccountKeyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
