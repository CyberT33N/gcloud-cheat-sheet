# `roles/dataplex.viewer`

Read access to Dataplex Universal Catalog resources, except for catalog resources like entries, entry groups, and glossaries.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.viewer` |
| Title | Dataplex Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.viewer` grants 41 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [dataplex](permissions/dataplex/overview.md) | 40 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
