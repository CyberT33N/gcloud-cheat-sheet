# `roles/securedlandingzone.bqdwProjectRemediator`

Access to modify (remediate) resources in SLZ BQDW Blueprint at Project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securedlandingzone.bqdwProjectRemediator` |
| Title | SLZ BQDW Blueprint Project Level Remediator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 23 |
| Service | [securedlandingzone](../overview.md) |

## Permissions

`roles/securedlandingzone.bqdwProjectRemediator` grants 23 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 4 |
| [cloudkms](permissions/cloudkms/overview.md) | 7 |
| [pubsub](permissions/pubsub/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securedlandingzone.bqdwProjectRemediator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
