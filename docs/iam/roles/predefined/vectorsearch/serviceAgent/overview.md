# `roles/vectorsearch.serviceAgent`

Gives Vector Search access to read Cloud Storage buckets, read/create objects, use Vertex Models, and call Discovery Engine RankService.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vectorsearch.serviceAgent` |
| Title | Vector Search Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [vectorsearch](../overview.md) |

## Permissions

`roles/vectorsearch.serviceAgent` grants 15 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 3 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 4 |
| [vectorsearch](permissions/vectorsearch/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vectorsearch.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
