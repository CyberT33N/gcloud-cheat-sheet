# `roles/discoveryengine.editor`

Grants read and write access to all discovery engine resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.editor` |
| Title | Discovery Engine Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 166 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.editor` grants 166 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [discoveryengine](permissions/discoveryengine/overview.md) | 164 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
