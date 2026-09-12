# `roles/cloudkms.expertRawPKCS1`

Enables raw PKCS#1 keys management.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.expertRawPKCS1` |
| Title | Cloud KMS Expert Raw PKCS#1 Key Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.expertRawPKCS1` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.expertRawPKCS1 --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
