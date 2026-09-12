# `roles/containerscanning.ServiceAgent`

Gives Container Scanner the access it needs to analyzecontainers for vulnerabilities and create occurrences using the Container Analysis API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/containerscanning.ServiceAgent` |
| Title | Container Scanner Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [containerscanning](../overview.md) |

## Permissions

`roles/containerscanning.ServiceAgent` grants 42 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/containerscanning.ServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
