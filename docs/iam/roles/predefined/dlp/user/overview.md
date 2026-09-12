# `roles/dlp.user`

Inspect, Redact, and De-identify Content

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dlp.user` |
| Title | DLP User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [dlp](../overview.md) |

## Permissions

`roles/dlp.user` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dlp](permissions/dlp/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dlp.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
