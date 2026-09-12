# `roles/discoveryengine.podcastApiUser`

Grants user-level access to the Podcast resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/discoveryengine.podcastApiUser` |
| Title | Podcast API User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 106 |
| Service | [discoveryengine](../overview.md) |

## Permissions

`roles/discoveryengine.podcastApiUser` grants 106 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [businessaicode](permissions/businessaicode/overview.md) | 5 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 13 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 85 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/discoveryengine.podcastApiUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
