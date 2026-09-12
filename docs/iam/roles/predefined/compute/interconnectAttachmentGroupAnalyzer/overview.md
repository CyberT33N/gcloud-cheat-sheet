# `roles/compute.interconnectAttachmentGroupAnalyzer`

Analyze Interconnect Attachment Groups via their GetOperationalStatus method.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.interconnectAttachmentGroupAnalyzer` |
| Title | Interconnect Attachment Group Analyzer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.interconnectAttachmentGroupAnalyzer` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.interconnectAttachmentGroupAnalyzer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
