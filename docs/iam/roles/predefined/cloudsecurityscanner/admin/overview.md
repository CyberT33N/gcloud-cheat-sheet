# `roles/cloudsecurityscanner.admin`

Full access to all Web Security Scanner resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsecurityscanner.admin` |
| Title | Web Security Scanner Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [cloudsecurityscanner](../overview.md) |

## Permissions

`roles/cloudsecurityscanner.admin` grants 27 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [cloudsecurityscanner](permissions/cloudsecurityscanner/overview.md) | 13 |
| [compute](permissions/compute/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsecurityscanner.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
