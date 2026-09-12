# `roles/apihub.admin`

Full access to all API hub resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apihub.admin` |
| Title | Cloud API Hub Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 127 |
| Service | [apihub](../overview.md) |

## Permissions

`roles/apihub.admin` grants 127 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 1 |
| [apihub](permissions/apihub/overview.md) | 113 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apihub.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
