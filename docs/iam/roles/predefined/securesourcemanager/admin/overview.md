# `roles/securesourcemanager.admin`

Full access to all Secure Source Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.admin` |
| Title | Secure Source Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 80 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.admin` grants 80 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 73 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
