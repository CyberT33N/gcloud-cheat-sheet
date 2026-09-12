# `roles/discoveryengine.agentspaceAdmin`

Grants admin-level access to Gemini Enterprise resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.agentspaceAdmin` |
| Title | Gemini Enterprise Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 446 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.agentspaceAdmin` grants 446 permissions across 11 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 84 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 14 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 2 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 279 |
| [logging](permissions/logging/overview.md) | 26 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [observability](permissions/observability/overview.md) | 6 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.agentspaceAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
