# `roles/developerconnect.insightsAgent`

Allow Developer Connect to access SDLC information.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.insightsAgent` |
| Title | Developer Connect Insights Config Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.insightsAgent` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 7 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.insightsAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
