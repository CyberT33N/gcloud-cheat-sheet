# `roles/assuredoss.user`

Access to use Assured OSS.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredoss.user` |
| Title | Assured OSS User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [assuredoss](../overview.md) |

## Permissions

`roles/assuredoss.user` grants 41 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [assuredoss](permissions/assuredoss/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredoss.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
