# `roles/storage.admin`

Grants full control of buckets and objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.admin` |
| Title | Storage Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 113 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.admin` grants 113 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
