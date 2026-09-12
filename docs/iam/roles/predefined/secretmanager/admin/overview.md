# `roles/secretmanager.admin`

Full access to administer Secret Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/secretmanager.admin` |
| Title | Secret Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [secretmanager](../overview.md) |

## Permissions

`roles/secretmanager.admin` grants 29 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [secretmanager](permissions/secretmanager/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/secretmanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
