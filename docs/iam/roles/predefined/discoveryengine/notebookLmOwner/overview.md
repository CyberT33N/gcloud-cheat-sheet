# `roles/discoveryengine.notebookLmOwner`

Grants full access to Cloud NotebookLM resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.notebookLmOwner` |
| Title | Cloud NotebookLM Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 32 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.notebookLmOwner` grants 32 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [discoveryengine](permissions/discoveryengine/overview.md) | 30 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.notebookLmOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
