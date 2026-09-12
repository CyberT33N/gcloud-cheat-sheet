# `roles/ids.admin`

Full access to Cloud IDS all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ids.admin` |
| Title | Cloud IDS Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 15 |
| Service | [ids](../overview.md) |

## Permissions

`roles/ids.admin` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ids](permissions/ids/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ids.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
