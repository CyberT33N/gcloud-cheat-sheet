# `roles/spanner.admin`

Full control of Cloud Spanner resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spanner.admin` |
| Title | Cloud Spanner Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 93 |
| Service | [spanner](../overview.md) |

## Permissions

`roles/spanner.admin` grants 93 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [spanner](permissions/spanner/overview.md) | 84 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spanner.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
