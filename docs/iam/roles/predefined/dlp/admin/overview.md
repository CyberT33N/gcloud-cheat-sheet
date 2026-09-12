# `roles/dlp.admin`

Administer DLP including jobs and templates.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dlp.admin` |
| Title | DLP Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 66 |
| Service | [dlp](../overview.md) |

## Permissions

`roles/dlp.admin` grants 66 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dlp](permissions/dlp/overview.md) | 63 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dlp.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
