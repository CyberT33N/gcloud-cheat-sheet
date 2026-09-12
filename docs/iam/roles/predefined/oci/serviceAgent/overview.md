# `roles/oci.serviceAgent`

Grants Oracle Database@Google Cloud access to services and APIs in the user project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oci.serviceAgent` |
| Title | Oracle Database@Google Cloud Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 104 |
| Service | [oci](../overview.md) |

## Permissions

`roles/oci.serviceAgent` grants 104 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 45 |
| [dns](permissions/dns/overview.md) | 41 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 7 |
| [oracledatabase](permissions/oracledatabase/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oci.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
