# `roles/clouddeploy.admin`

Full control of Cloud Deploy resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddeploy.admin` |
| Title | Cloud Deploy Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 70 |
| Service | [clouddeploy](../overview.md) |

## Permissions

`roles/clouddeploy.admin` grants 70 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clouddeploy](permissions/clouddeploy/overview.md) | 68 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddeploy.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
