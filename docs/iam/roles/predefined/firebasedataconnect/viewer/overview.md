# `roles/firebasedataconnect.viewer`

Readonly access to Firebase SQL Connect API resources. This role does not grant any access to data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedataconnect.viewer` |
| Title | Firebase SQL Connect API Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 19 |
| Service | [firebasedataconnect](../overview.md) |

## Permissions

`roles/firebasedataconnect.viewer` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebasedataconnect](permissions/firebasedataconnect/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedataconnect.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
