# `roles/eventarc.eventReceiver`

Can receive events from all event providers.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/eventarc.eventReceiver` |
| Title | Eventarc Event Receiver |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [eventarc](../overview.md) |

## Permissions

`roles/eventarc.eventReceiver` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [eventarc](permissions/eventarc/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/eventarc.eventReceiver --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
