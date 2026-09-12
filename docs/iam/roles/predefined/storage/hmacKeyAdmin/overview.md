# `roles/storage.hmacKeyAdmin`

Grants full control over HMAC keys in a project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.hmacKeyAdmin` |
| Title | Storage HMAC Key Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.hmacKeyAdmin` grants 9 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.hmacKeyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
