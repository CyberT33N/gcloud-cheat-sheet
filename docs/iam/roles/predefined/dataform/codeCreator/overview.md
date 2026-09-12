# `roles/dataform.codeCreator`

Access only to private and shared code resources. The permissions in the Code Creator let you create and list code in Dataform, and access only the code that you created and code that was explicitly shared with you.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataform.codeCreator` |
| Title | Code Creator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [dataform](../overview.md) |

## Permissions

`roles/dataform.codeCreator` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataform](permissions/dataform/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataform.codeCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
