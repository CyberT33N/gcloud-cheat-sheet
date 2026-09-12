# `roles/eventarc.publisher`

Can publish events to Eventarc channels.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/eventarc.publisher` |
| Title | Eventarc Publisher |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [eventarc](../overview.md) |

## Permissions

`roles/eventarc.publisher` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [eventarc](permissions/eventarc/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/eventarc.publisher --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
