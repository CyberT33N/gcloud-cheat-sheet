# `roles/binaryauthorization.serviceAgent`

Can read Notes and Occurrences from the Container Analysis Service to find and verify signatures.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/binaryauthorization.serviceAgent` |
| Title | Binary Authorization Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [binaryauthorization](../overview.md) |

## Permissions

`roles/binaryauthorization.serviceAgent` grants 20 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 2 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 5 |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/binaryauthorization.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
