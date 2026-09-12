# `roles/riskmanager.serviceAgent`

Service agent that grants Risk Manager service access to fetch findings for generating Reports

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/riskmanager.serviceAgent` |
| Title | Risk Manager Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 644 |
| Service | [riskmanager](../overview.md) |

## Permissions

`roles/riskmanager.serviceAgent` grants 644 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 564 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |
| [securitycenter](permissions/securitycenter/overview.md) | 49 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/riskmanager.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
