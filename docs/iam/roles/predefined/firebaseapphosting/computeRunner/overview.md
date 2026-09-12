# `roles/firebaseapphosting.computeRunner`

Contains the basic necessary permissions for building and running Apps on Firebase App Hosting. Gives access to get and update App Hosting builds, upload artifacts to Artifact Registry and Storage, write logs. Intended to be granted to the user-supplied App Hosting Compute service account.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseapphosting.computeRunner` |
| Title | Firebase App Hosting Compute Runner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 99 |
| Service | [firebaseapphosting](../overview.md) |

## Permissions

`roles/firebaseapphosting.computeRunner` grants 99 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 44 |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [developerconnect](permissions/developerconnect/overview.md) | 3 |
| [firebaseapphosting](permissions/firebaseapphosting/overview.md) | 14 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 25 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseapphosting.computeRunner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
