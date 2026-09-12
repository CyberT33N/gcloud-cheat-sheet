# `roles/stream.contentAdmin`

Full access to all StreamContent resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/stream.contentAdmin` |
| Title | Stream Content Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [stream](../overview.md) |

## Permissions

`roles/stream.contentAdmin` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stream](permissions/stream/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/stream.contentAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
