# `roles/netapp.admin`

Full access to Google Cloud NetApp Volumes resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/netapp.admin` |
| Title | Google Cloud NetApp Volumes Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 92 |
| Service | [netapp](../overview.md) |

## Permissions

`roles/netapp.admin` grants 92 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 7 |
| [netapp](permissions/netapp/overview.md) | 83 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/netapp.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
