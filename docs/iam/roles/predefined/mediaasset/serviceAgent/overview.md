# `roles/mediaasset.serviceAgent`

Downloads and uploads media files from and to customer GCS buckets.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/mediaasset.serviceAgent` |
| Title | Media Asset Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [mediaasset](../overview.md) |

## Permissions

`roles/mediaasset.serviceAgent` grants 8 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 3 |
| [transcoder](permissions/transcoder/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/mediaasset.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
