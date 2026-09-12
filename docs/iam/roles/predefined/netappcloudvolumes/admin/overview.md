# `roles/netappcloudvolumes.admin`

This role is managed by NetApp, not Google.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/netappcloudvolumes.admin` |
| Title | NetApp Cloud Volumes Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 31 |
| Service | [netappcloudvolumes](../overview.md) |

## Permissions

`roles/netappcloudvolumes.admin` grants 31 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudvolumesgcp-api.netapp.com](permissions/cloudvolumesgcp-api.netapp.com/overview.md) | 29 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/netappcloudvolumes.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
