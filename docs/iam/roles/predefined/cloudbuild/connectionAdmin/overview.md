# `roles/cloudbuild.connectionAdmin`

Can manage connections and repositories.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.connectionAdmin` |
| Title | Cloud Build Connection Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.connectionAdmin` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 15 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.connectionAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
