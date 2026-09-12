# `roles/secretmanager.secretVersionAdder`

Allows adding versions to existing secrets.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/secretmanager.secretVersionAdder` |
| Title | Secret Manager Secret Version Adder |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [secretmanager](../overview.md) |

## Permissions

`roles/secretmanager.secretVersionAdder` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [secretmanager](permissions/secretmanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/secretmanager.secretVersionAdder --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
