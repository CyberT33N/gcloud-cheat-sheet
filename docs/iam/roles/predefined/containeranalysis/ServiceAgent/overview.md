# `roles/containeranalysis.ServiceAgent`

Gives Container Analysis API the access it needs to function

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/containeranalysis.ServiceAgent` |
| Title | Container Analysis Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 89 |
| Service | [containeranalysis](../overview.md) |

## Permissions

`roles/containeranalysis.ServiceAgent` grants 89 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 6 |
| [pubsub](permissions/pubsub/overview.md) | 37 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/containeranalysis.ServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
