# `roles/cloudaicompanion.admin`

Admin role for Gemini for Google Cloud

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudaicompanion.admin` |
| Title | Gemini for Google Cloud Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 100 |
| Service | [cloudaicompanion](../overview.md) |

## Permissions

`roles/cloudaicompanion.admin` grants 100 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 98 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudaicompanion.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
