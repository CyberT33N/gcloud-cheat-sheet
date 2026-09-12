# `roles/cloudbuild.readTokenAccessor`

Can view the connection and access its read-only token.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.readTokenAccessor` |
| Title | Cloud Build Read Only Token Accessor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.readTokenAccessor` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.readTokenAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
