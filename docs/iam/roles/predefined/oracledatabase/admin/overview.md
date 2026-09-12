# `roles/oracledatabase.admin`

Grants full access to manage all Oracle Database resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oracledatabase.admin` |
| Title | Oracle Database@Google Cloud admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 106 |
| Service | [oracledatabase](../overview.md) |

## Permissions

`roles/oracledatabase.admin` grants 106 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [oracledatabase](permissions/oracledatabase/overview.md) | 104 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oracledatabase.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
