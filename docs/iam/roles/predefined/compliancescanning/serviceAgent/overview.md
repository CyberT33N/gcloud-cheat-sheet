# `roles/compliancescanning.serviceAgent`

Gives Compliance Scanning the access it needs to analyze containers and VMs for compliance and create occurrences using the Container Analysis API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compliancescanning.serviceAgent` |
| Title | Compliance Scanning Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 52 |
| Service | [compliancescanning](../overview.md) |

## Permissions

`roles/compliancescanning.serviceAgent` grants 52 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 26 |
| [compute](permissions/compute/overview.md) | 11 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compliancescanning.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
