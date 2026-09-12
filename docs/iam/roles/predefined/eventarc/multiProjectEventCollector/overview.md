# `roles/eventarc.multiProjectEventCollector`

Can collect events from multiple projects in an org for a source resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/eventarc.multiProjectEventCollector` |
| Title | Eventarc Event Collector |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1 |
| Service | [eventarc](../overview.md) |

## Permissions

`roles/eventarc.multiProjectEventCollector` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [eventarc](permissions/eventarc/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/eventarc.multiProjectEventCollector --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
