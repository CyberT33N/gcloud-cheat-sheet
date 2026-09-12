# IAM Conventions

General conventions for the whole `docs/iam` area — the IAM bounded context of this reference project. Binding sub-area rules live in the referenced child conventions.

## Area map (table of contents)

- [Roles conventions](roles/CONVENTIONS.md) — `roles/` mirrors the official IAM roles structure 1:1 (`basic/`, `predefined/`, `custom/`).
- [Permissions conventions](permissions/CONVENTIONS.md) — `permissions/` mirrors the global IAM permission namespace 1:1, exactly once per permission.

## Architecture rationale (why two sibling areas)

Domain-driven design separates the two IAM entities into two sibling bounded contexts, because their identity and ownership differ:

- **Permission** — a global, Google-managed entity. Its identity is its name; its meaning is identical everywhere. It is documented exactly once, in `permissions/`.
- **Role** — an aggregate whose state *is* its permission set. The set differs per role, so the assignment is materialized per role, in `roles/<role>/permissions/<service>/overview.md`.
- **The relation between them** is materialized as two generated read models of one truth: the per-role assignment pages (question: "what does this role grant?") and the reverse index on each central permission page (question: "which roles grant this permission?").

The single source of truth for both areas is the IAM API dataset (`roles.list` with `view=FULL`, plus `roles.get` for basic roles), executed with the locally installed Google Cloud SDK and cross-checked against the official IAM documentation. Every `overview.md` in this area is a regenerated projection of that dataset — never a hand-maintained copy.

## Shared IAM rules

- **Generated vs. hand-written:** `overview.md` files and `.git-keep` placeholders are generator-owned and never hand-edited. Every other file (conventions, topic files such as `troubleshooting.md`, `dependencies.md`, `incompatible-roles.md`) is hand-written, survives clean rebuilds, and is linked automatically by the generator in a `## Topics` section.
- **Completeness is binary:** every role and every permission present in the dataset is documented; nothing else is documented. Fields the API does not publish are marked factually, never invented.
- **Naming:** folder names equal the official identifiers byte-exactly (role ID segments, permission segments, DNS-form service names). They are tool-fixed identifiers and are never restyled.
- **Lifecycle:** maintenance is regeneration — refresh the dataset, rerun the generator, then run the independent verifier (assignment coverage, central coverage, reverse-index consistency, link resolution). Hand edits to generated pages are forbidden; fix the generator instead.

## Parent conventions

- [Documentation conventions](../CONVENTIONS.md) — global shared-kernel rules and the project-wide conventions TOC.
