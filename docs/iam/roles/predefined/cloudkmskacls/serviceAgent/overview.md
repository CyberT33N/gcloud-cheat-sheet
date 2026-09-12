# `roles/cloudkmskacls.serviceAgent`

Grants Cloud KMS KACLS Service Agent access to KMS resource permissions to perform DEK encryption/decryption.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkmskacls.serviceAgent` |
| Title | Cloud KMS KACLS Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [cloudkmskacls](../overview.md) |

## Permissions

`roles/cloudkmskacls.serviceAgent` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkmskacls.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
