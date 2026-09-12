# `roles/assuredoss.admin`

Access to use Assured OSS and manage configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredoss.admin` |
| Title | Assured OSS Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 79 |
| Service | [assuredoss](../overview.md) |

## Permissions

`roles/assuredoss.admin` grants 79 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 33 |
| [assuredoss](permissions/assuredoss/overview.md) | 10 |
| [iam](permissions/iam/overview.md) | 3 |
| [pubsub](permissions/pubsub/overview.md) | 19 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredoss.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
