# `roles/containersecurity.admin`

Admin role for containersecurity

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/containersecurity.admin` |
| Title | Containersecurity Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [containersecurity](../overview.md) |

## Permissions

`roles/containersecurity.admin` grants 7 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 1 |
| [containersecurity](permissions/containersecurity/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/containersecurity.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
