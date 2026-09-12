# `roles/cloudkms.cryptoKeyEncrypter`

Enables Encrypt operations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.cryptoKeyEncrypter` |
| Title | Cloud KMS CryptoKey Encrypter |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.cryptoKeyEncrypter` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.cryptoKeyEncrypter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
