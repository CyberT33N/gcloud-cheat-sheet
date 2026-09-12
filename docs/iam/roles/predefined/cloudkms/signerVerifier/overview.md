# `roles/cloudkms.signerVerifier`

Enables Sign, Verify, and GetPublicKey operations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.signerVerifier` |
| Title | Cloud KMS CryptoKey Signer/Verifier |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.signerVerifier` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.signerVerifier --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
