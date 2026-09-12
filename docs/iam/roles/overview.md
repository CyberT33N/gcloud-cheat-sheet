# IAM roles

[INTENT: NAVIGATION]

Complete reference of all IAM roles. A role is a collection of IAM permissions; granting a role to a principal grants all permissions in the role.

## Role types

- [Basic roles](basic/overview.md) — 6 roles: Admin, Writer, Reader (current) and Owner, Editor, Viewer (legacy)

- [Predefined roles](predefined/overview.md) — 2390 roles across 370 services, mirrored 1:1 from the role ID hierarchy

- [Custom roles](custom/overview.md) — user-defined roles (concept page; custom roles have no fixed instances)

## Related areas

- [Permissions](../permissions/overview.md) — central catalog of all IAM permissions; role pages link every granted permission into this catalog

## Data provenance

- Source: IAM REST API `roles.list` (`view=FULL`) plus `roles.get` for basic roles, executed with the locally installed Google Cloud SDK 580.0.0 on 2026-09-12.

- Completeness: 2396 roles total (6 basic + 2390 predefined), zero duplicates.

- Conventions for this area: [CONVENTIONS.md](CONVENTIONS.md)

## Official documentation

- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
