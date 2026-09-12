# `roles/proximitybeacon.attachmentEditor`

Can create and delete attachments; can list and get a project's beacons; can list a project's namespaces.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/proximitybeacon.attachmentEditor` |
| Title | Beacon Attachment Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [proximitybeacon](../overview.md) |

## Permissions

`roles/proximitybeacon.attachmentEditor` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [proximitybeacon](permissions/proximitybeacon/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/proximitybeacon.attachmentEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
