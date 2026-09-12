# `roles/cloudiot.serviceAgent`

Grants the ability to manage Cloud IoT Core resources, including publishing data to Cloud Pub/Sub and writing device activity logs to Stackdriver. Warning: If this role is removed from the Cloud IoT service account, Cloud IoT Core will be unable to publish data or write device activity logs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudiot.serviceAgent` |
| Title | Cloud IoT Core Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [cloudiot](../overview.md) |

## Permissions

`roles/cloudiot.serviceAgent` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 2 |
| [pubsub](permissions/pubsub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudiot.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
