# `roles/cloudkms.ekmConnectionsAdmin`

Enables management of EkmConnections.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudkms.ekmConnectionsAdmin` |
| Title | Cloud KMS EkmConnections Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [cloudkms](../overview.md) |

## Permissions

`roles/cloudkms.ekmConnectionsAdmin` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudkms.ekmConnectionsAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
