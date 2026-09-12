# `roles/oracledatabase.viewer`

Grants view access to all Oracle Database resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oracledatabase.viewer` |
| Title | Oracle Database@Google Cloud viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 46 |
| Service | [oracledatabase](../overview.md) |

## Permissions

`roles/oracledatabase.viewer` grants 46 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [oracledatabase](permissions/oracledatabase/overview.md) | 44 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oracledatabase.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
