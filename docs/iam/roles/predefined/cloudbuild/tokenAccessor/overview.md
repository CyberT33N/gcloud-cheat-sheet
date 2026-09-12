# `roles/cloudbuild.tokenAccessor`

Can view the connection and access its read/write and read-only tokens.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.tokenAccessor` |
| Title | Cloud Build Token Accessor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.tokenAccessor` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.tokenAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
