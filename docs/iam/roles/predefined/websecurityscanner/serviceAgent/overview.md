# `roles/websecurityscanner.serviceAgent`

Gives the Cloud Web Security Scanner service account access to compute engine details and app engine details.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/websecurityscanner.serviceAgent` |
| Title | Cloud Web Security Scanner Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [websecurityscanner](../overview.md) |

## Permissions

`roles/websecurityscanner.serviceAgent` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/websecurityscanner.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
