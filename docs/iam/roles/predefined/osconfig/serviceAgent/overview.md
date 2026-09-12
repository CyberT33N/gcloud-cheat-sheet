# `roles/osconfig.serviceAgent`

Grants OS Config Service Account access to Google Compute Engine instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/osconfig.serviceAgent` |
| Title | Cloud OS Config Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [osconfig](../overview.md) |

## Permissions

`roles/osconfig.serviceAgent` grants 27 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 9 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 11 |
| [iam](permissions/iam/overview.md) | 1 |
| [osconfig](permissions/osconfig/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/osconfig.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
