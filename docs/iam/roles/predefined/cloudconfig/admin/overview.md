# `roles/cloudconfig.admin`

Full access to Firebase Remote Config resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudconfig.admin` |
| Title | Firebase Remote Config Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [cloudconfig](../overview.md) |

## Permissions

`roles/cloudconfig.admin` grants 7 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudconfig](permissions/cloudconfig/overview.md) | 2 |
| [firebase](permissions/firebase/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudconfig.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
