# `roles/stream.serviceAgent`

Gives Immersive Stream for XR access to the required resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/stream.serviceAgent` |
| Title | Stream Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [stream](../overview.md) |

## Permissions

`roles/stream.serviceAgent` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/stream.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
