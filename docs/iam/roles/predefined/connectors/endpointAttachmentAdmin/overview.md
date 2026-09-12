# `roles/connectors.endpointAttachmentAdmin`

Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Admin access to Connectors Endpoint Attachment resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.endpointAttachmentAdmin` |
| Title | Connectors Endpoint Attachment Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.endpointAttachmentAdmin` grants 9 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.endpointAttachmentAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
