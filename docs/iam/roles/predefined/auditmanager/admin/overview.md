# `roles/auditmanager.admin`

Full access to Audit Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/auditmanager.admin` |
| Title | Audit Manager Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 27 |
| Service | [auditmanager](../overview.md) |

## Permissions

`roles/auditmanager.admin` grants 27 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [auditmanager](permissions/auditmanager/overview.md) | 21 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/auditmanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
