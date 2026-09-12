# `roles/oracledatabase.autonomousDatabaseViewer`

Grants read access to see all Autonomous Database resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oracledatabase.autonomousDatabaseViewer` |
| Title | Oracle Database@Google Cloud Autonomous Database Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [oracledatabase](../overview.md) |

## Permissions

`roles/oracledatabase.autonomousDatabaseViewer` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [oracledatabase](permissions/oracledatabase/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oracledatabase.autonomousDatabaseViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
