# `roles/ids.viewer`

Read-only access to Cloud IDS all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ids.viewer` |
| Title | Cloud IDS Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [ids](../overview.md) |

## Permissions

`roles/ids.viewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ids](permissions/ids/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ids.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
