# `roles/cloudsupport.techSupportEditor`

Full read-write access to technical support cases (applicable for GCP Customer Care and Maps support).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsupport.techSupportEditor` |
| Title | Tech Support Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [cloudsupport](../overview.md) |

## Permissions

`roles/cloudsupport.techSupportEditor` grants 10 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudsupport](permissions/cloudsupport/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsupport.techSupportEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
