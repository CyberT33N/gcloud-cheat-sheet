# Custom roles

[INTENT: REFERENCE]

Custom roles are user-defined IAM roles that bundle one or more supported permissions to meet specific needs. They enforce the principle of least privilege where no predefined role fits.

## Key facts (official documentation)

- Custom roles are created at the organization or project level only; folder-level custom roles are not supported.
- Limits: 300 custom roles per organization and 300 per project.
- A custom role can only be granted within the project or organization in which it was created.
- Permission support levels for custom roles: `SUPPORTED`, `TESTING`, `NOT_SUPPORTED`.
- Launch stages for custom roles: `ALPHA`, `BETA`, `GA`, `DEPRECATED`, plus `DISABLED` to disable a role.
- A deleted custom role ID stays blocked until the 44-day deletion process completes.

## Manage custom roles with the gcloud CLI

The command surface lives in the CLI area under `gcloud iam roles` (`create`, `update`, `delete`, `undelete`, `copy`, `describe`, `list`): see the [CLI reference](../../../cli/overview.md) and the verified [iam roles describe](../../../cli/iam/roles/describe/overview.md) page.

## Official documentation

- [Roles overview — custom roles](https://cloud.google.com/iam/docs/roles-overview)
- [Create and manage custom roles](https://cloud.google.com/iam/docs/creating-custom-roles)
