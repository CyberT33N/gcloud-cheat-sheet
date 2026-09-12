# `roles/healthcare.attributeDefinitionReader`

Read AttributeDefinition objects in a consent store.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/healthcare.attributeDefinitionReader` |
| Title | Healthcare Attribute Definition Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [healthcare](../overview.md) |

## Permissions

`roles/healthcare.attributeDefinitionReader` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [healthcare](permissions/healthcare/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/healthcare.attributeDefinitionReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
