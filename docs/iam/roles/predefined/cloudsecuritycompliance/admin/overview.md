# `roles/cloudsecuritycompliance.admin`

Full access to Compliance Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsecuritycompliance.admin` |
| Title | Compliance Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 73 |
| Service | [cloudsecuritycompliance](../overview.md) |

## Permissions

`roles/cloudsecuritycompliance.admin` grants 73 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [auditmanager](permissions/auditmanager/overview.md) | 20 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 51 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsecuritycompliance.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
