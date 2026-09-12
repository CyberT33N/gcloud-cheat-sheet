# `roles/configdelivery.resourceBundlePublisher`

Grants read and write permissions to Config Delivery ResourceBundles and Releases.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/configdelivery.resourceBundlePublisher` |
| Title | Config Delivery Resource Bundle Publisher |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [configdelivery](../overview.md) |

## Permissions

`roles/configdelivery.resourceBundlePublisher` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [configdelivery](permissions/configdelivery/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/configdelivery.resourceBundlePublisher --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
