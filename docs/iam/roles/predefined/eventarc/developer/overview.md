# `roles/eventarc.developer`

Access to read and write Eventarc resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/eventarc.developer` |
| Title | Eventarc Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 69 |
| Service | [eventarc](../overview.md) |

## Permissions

`roles/eventarc.developer` grants 69 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [eventarc](permissions/eventarc/overview.md) | 67 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/eventarc.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
