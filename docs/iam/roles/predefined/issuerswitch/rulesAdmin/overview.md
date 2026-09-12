# `roles/issuerswitch.rulesAdmin`

Full access to issuer switch rules

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/issuerswitch.rulesAdmin` |
| Title | Issuerswitch Rules Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [issuerswitch](../overview.md) |

## Permissions

`roles/issuerswitch.rulesAdmin` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [issuerswitch](permissions/issuerswitch/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/issuerswitch.rulesAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
