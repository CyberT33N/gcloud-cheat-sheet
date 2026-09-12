# `roles/healthcare.annotationReader`

Read and list annotations in an Annotation store.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/healthcare.annotationReader` |
| Title | Healthcare Annotation Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [healthcare](../overview.md) |

## Permissions

`roles/healthcare.annotationReader` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [healthcare](permissions/healthcare/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/healthcare.annotationReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
