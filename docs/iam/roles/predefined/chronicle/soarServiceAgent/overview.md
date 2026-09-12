# `roles/chronicle.soarServiceAgent`

Gives Chronicle SOAR the ability to perform remediation on Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.soarServiceAgent` |
| Title | Chronicle SOAR Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 37 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.soarServiceAgent` grants 37 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 12 |
| [iam](permissions/iam/overview.md) | 2 |
| [recommender](permissions/recommender/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.soarServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
