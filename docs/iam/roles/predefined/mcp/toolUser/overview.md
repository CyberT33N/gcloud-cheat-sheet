# `roles/mcp.toolUser`

Gives permission to call tools on any MCP server enabled by the parent project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/mcp.toolUser` |
| Title | MCP Tool User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [mcp](../overview.md) |

## Permissions

`roles/mcp.toolUser` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [mcp](permissions/mcp/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/mcp.toolUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
