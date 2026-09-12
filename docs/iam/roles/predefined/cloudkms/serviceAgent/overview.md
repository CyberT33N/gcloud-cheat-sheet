# `roles/cloudkms.serviceAgent`

Gives Cloud KMS service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.serviceAgent` |
| Title | Cloud KMS Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.serviceAgent` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 4 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
