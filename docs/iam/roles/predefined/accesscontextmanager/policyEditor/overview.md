# `roles/accesscontextmanager.policyEditor`

Edit access to policies.  Create, edit, and change access levels, access zones and authorized orgs descs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/accesscontextmanager.policyEditor` |
| Title | Access Context Manager Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 28 |
| Service | [accesscontextmanager](../overview.md) |

## Permissions

`roles/accesscontextmanager.policyEditor` grants 28 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accesscontextmanager](permissions/accesscontextmanager/overview.md) | 24 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/accesscontextmanager.policyEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
