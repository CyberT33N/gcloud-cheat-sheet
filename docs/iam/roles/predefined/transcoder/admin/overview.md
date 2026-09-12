# `roles/transcoder.admin`

Full access to all transcoder resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/transcoder.admin` |
| Title | Transcoder Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [transcoder](../overview.md) |

## Permissions

`roles/transcoder.admin` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [transcoder](permissions/transcoder/overview.md) | 16 |

## Inspect this role live

```shell
gcloud iam roles describe roles/transcoder.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
