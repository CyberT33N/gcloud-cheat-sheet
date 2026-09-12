# `roles/apigee.admin`

Full access to all apigee resource features

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.admin` |
| Title | Apigee Organization Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 432 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.admin` grants 432 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 304 |
| [apihub](permissions/apihub/overview.md) | 113 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
