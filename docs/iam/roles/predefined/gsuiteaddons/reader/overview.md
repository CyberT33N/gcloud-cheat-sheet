# `roles/gsuiteaddons.reader`

Read-only access to Google Workspace Add-ons resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gsuiteaddons.reader` |
| Title | Google Workspace Add-ons Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [gsuiteaddons](../overview.md) |

## Permissions

`roles/gsuiteaddons.reader` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gsuiteaddons](permissions/gsuiteaddons/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gsuiteaddons.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
