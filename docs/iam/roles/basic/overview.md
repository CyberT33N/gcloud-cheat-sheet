# Basic roles

[INTENT: NAVIGATION]

Basic roles are highly permissive roles that give broad access to Google Cloud resources. The current basic roles are Admin (`roles/admin`), Writer (`roles/writer`) and Reader (`roles/reader`); the legacy basic roles (formerly primitive roles) are Owner (`roles/owner`), Editor (`roles/editor`) and Viewer (`roles/viewer`).

> **Caution (official guidance):** Basic roles include thousands of permissions across all Google Cloud services. In production environments, do not grant basic roles unless there is no alternative; grant the most limited predefined or custom roles that meet the need.

## Roles

| Role | Title | Launch stage | Included permissions |
| --- | --- | --- | --- |
| [`roles/owner`](owner/overview.md) | Owner | `GA` | 13702 |
| [`roles/editor`](editor/overview.md) | Editor | `GA` | 12086 |
| [`roles/viewer`](viewer/overview.md) | Viewer | `GA` | 6130 |
| [`roles/admin`](admin/overview.md) | Admin | Preview (per the official roles overview) | 13767 |
| [`roles/writer`](writer/overview.md) | Writer | Preview (per the official roles overview) | 12122 |
| [`roles/reader`](reader/overview.md) | Reader | Preview (per the official roles overview) | 6147 |

## Official documentation

- [Roles overview — basic roles](https://cloud.google.com/iam/docs/roles-overview)
