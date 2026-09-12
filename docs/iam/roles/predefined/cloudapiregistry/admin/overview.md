# `roles/cloudapiregistry.admin`

Read/write access to Cloud API Registry resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudapiregistry.admin` |
| Title | Cloud API Registry Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [cloudapiregistry](../overview.md) |

## Permissions

`roles/cloudapiregistry.admin` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudapiregistry](permissions/cloudapiregistry/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudapiregistry.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
