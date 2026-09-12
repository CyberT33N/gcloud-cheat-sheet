# `roles/apihub.provisioningAdmin`

Full access to Cloud API hub provisioning related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apihub.provisioningAdmin` |
| Title | Cloud API hub Provisioning Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [apihub](../overview.md) |

## Permissions

`roles/apihub.provisioningAdmin` grants 27 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apihub](permissions/apihub/overview.md) | 20 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apihub.provisioningAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
