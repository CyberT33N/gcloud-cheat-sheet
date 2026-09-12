# `roles/dataplex.admin`

Full access to Dataplex Universal Catalog resources, except for catalog resources like entries and entry groups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.admin` |
| Title | Dataplex Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 193 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.admin` grants 193 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 3 |
| [dataplex](permissions/dataplex/overview.md) | 188 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
