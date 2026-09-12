# `roles/clouddebugger.agent`

Cloud Debugger agents are allowed to register and provide debug snapshot data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddebugger.agent` |
| Title | Cloud Debugger Agent |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 4 |
| Service | [clouddebugger](../overview.md) |

## Permissions

`roles/clouddebugger.agent` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clouddebugger](permissions/clouddebugger/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddebugger.agent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
