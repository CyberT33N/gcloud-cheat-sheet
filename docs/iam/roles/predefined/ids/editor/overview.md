# `roles/ids.editor`

Editor role for Cloud IDS

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ids.editor` |
| Title | Cloud IDS Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 14 |
| Service | [ids](../overview.md) |

## Permissions

`roles/ids.editor` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ids](permissions/ids/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ids.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
