# `roles/ces.client`

Query access to Gemini Enterprise for Customer Experience agents.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ces.client` |
| Title | Gemini Enterprise for Customer Experience Client |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [ces](../overview.md) |

## Permissions

`roles/ces.client` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ces](permissions/ces/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ces.client --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
