# `roles/firebasecrash.symbolMappingsAdmin`

Full read/write access to symbol mapping file resources for Firebase Crash Reporting.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasecrash.symbolMappingsAdmin` |
| Title | Firebase Crash Symbol Uploader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [firebasecrash](../overview.md) |

## Permissions

`roles/firebasecrash.symbolMappingsAdmin` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasecrash.symbolMappingsAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
