# `roles/cloudkms.orgServiceAgent`

Gives Cloud KMS organization-level service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.orgServiceAgent` |
| Title | Cloud KMS Organization Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.orgServiceAgent` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.orgServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
