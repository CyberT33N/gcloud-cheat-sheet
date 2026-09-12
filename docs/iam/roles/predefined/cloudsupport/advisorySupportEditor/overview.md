# `roles/cloudsupport.advisorySupportEditor`

Full read-write access to advisory support cases applicable for GCP Customer Care.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsupport.advisorySupportEditor` |
| Title | Advisory Support Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [cloudsupport](../overview.md) |

## Permissions

`roles/cloudsupport.advisorySupportEditor` grants 4 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudsupport](permissions/cloudsupport/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsupport.advisorySupportEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
