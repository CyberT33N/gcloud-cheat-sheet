# `roles/axt.admin`

Enable Access Transparency for Organization

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/axt.admin` |
| Title | Access Transparency Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [axt](../overview.md) |

## Permissions

`roles/axt.admin` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [axt](permissions/axt/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/axt.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
