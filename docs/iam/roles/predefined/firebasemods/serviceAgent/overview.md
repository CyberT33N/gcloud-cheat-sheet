# `roles/firebasemods.serviceAgent`

Grants Firebase Extensions API Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasemods.serviceAgent` |
| Title | Firebase Extensions API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 73 |
| Service | [firebasemods](../overview.md) |

## Permissions

`roles/firebasemods.serviceAgent` grants 73 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 1 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 2 |
| [cloudtasks](permissions/cloudtasks/overview.md) | 14 |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 30 |
| [eventarc](permissions/eventarc/overview.md) | 4 |
| [iam](permissions/iam/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [run](permissions/run/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasemods.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
