# `roles/configdelivery.configDeliveryViewer`

Grants read access to all Config Delivery resources. Lets users view existing fleet packages and resource bundles, but they will not be able to make any changes.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/configdelivery.configDeliveryViewer` |
| Title | ConfigDelivery Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [configdelivery](../overview.md) |

## Permissions

`roles/configdelivery.configDeliveryViewer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [configdelivery](permissions/configdelivery/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/configdelivery.configDeliveryViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
