# `roles/assuredoss.reader`

Access to use Assured OSS and view Assured OSS configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredoss.reader` |
| Title | Assured OSS Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 69 |
| Service | [assuredoss](../overview.md) |

## Permissions

`roles/assuredoss.reader` grants 69 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [assuredoss](permissions/assuredoss/overview.md) | 7 |
| [pubsub](permissions/pubsub/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredoss.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
