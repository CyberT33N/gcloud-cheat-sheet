# `roles/discoveryengine.agentspaceRestrictedUser`

Grants restricted user-level access to Gemini Enterprise resources, for fine-grained control over multiple Gemini Enterprise instances in the same project. Principals with this role will need to be granted an unrestricted user-level role (e.g. /agentspaceUser) on an Engine policy in order to use Gemini Enterprise.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.agentspaceRestrictedUser` |
| Title | Gemini Enterprise Restricted User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.agentspaceRestrictedUser` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [discoveryengine](permissions/discoveryengine/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.agentspaceRestrictedUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
