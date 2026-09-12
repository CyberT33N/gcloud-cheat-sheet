# `roles/servicehealth.admin`

Admin role for servicehealth

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicehealth.admin` |
| Title | Servicehealth Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [servicehealth](../overview.md) |

## Permissions

`roles/servicehealth.admin` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicehealth](permissions/servicehealth/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicehealth.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
