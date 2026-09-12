# `roles/iam.accessPolicyViewer`

Access Policy Viewer role, with permissions to read  access policies and view associated policy bindings

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.accessPolicyViewer` |
| Title | Access Policy Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.accessPolicyViewer` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.accessPolicyViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
