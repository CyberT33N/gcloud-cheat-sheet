# `roles/connectors.endpointAttachmentViewer`

Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Read-only access to Connectors Endpoint Attachment resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.endpointAttachmentViewer` |
| Title | Connectors Endpoint Attachment Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.endpointAttachmentViewer` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.endpointAttachmentViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
