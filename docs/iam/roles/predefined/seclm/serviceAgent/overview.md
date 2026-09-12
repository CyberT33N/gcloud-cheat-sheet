# `roles/seclm.serviceAgent`

Service agent used by SecLM to access resources used by SecLM Workbenches.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/seclm.serviceAgent` |
| Title | SecLM Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [seclm](../overview.md) |

## Permissions

`roles/seclm.serviceAgent` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 5 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/seclm.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
