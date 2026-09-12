# `roles/accesscontextmanager.policyReader`

Read access to policies, access levels, access zones and authorized orgs descs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/accesscontextmanager.policyReader` |
| Title | Access Context Manager Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [accesscontextmanager](../overview.md) |

## Permissions

`roles/accesscontextmanager.policyReader` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accesscontextmanager](permissions/accesscontextmanager/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/accesscontextmanager.policyReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
