# Documentation Conventions

Table of contents for the documentation architecture of this reference project. This file is the single entry point: it carries the global shared-kernel rules and references the area conventions. Area-specific binding rules live exclusively in the referenced area `CONVENTIONS.md` files.

## Global rules (shared kernel, binding for every area)

- **Language:** all file content is written in English.
- **Verification first:** only executed and verified content is documented. Unverified commands, flags, or role data are never written down.
- **No hallucination:** if information cannot be sourced from the official documentation or from the programmatic surface of the tool, it is not documented.
- **Sanitizing:** persisted content never contains real project IDs, organization names, resource IDs, tokens, user names, or internal hosts; semantic placeholders such as `<PROJECT_ID>` are used instead.
- **Naming:** folder and file names mirror the official names of the mirrored surface exactly (command tokens, role ID segments, permission segments). These official names are tool-fixed identifiers and are never restyled.
- **Decomposition over monoliths:** content is decomposed along the domain structure into folder hierarchies with `overview.md` table-of-contents pages. Monolithic files that mix thousands of entries on one page are forbidden; every level of a hierarchy carries its own navigable `overview.md`.
- **Single source of truth per concept:** a domain concept is documented exactly once, in the area that owns it. Other areas reference it by link instead of duplicating it (example: permissions are documented once in `iam/permissions/`; role pages link into that catalog).
- **Generated vs. hand-written surfaces:** generated pages (`overview.md`, `.git-keep`) are regenerated from verified data sources and never hand-edited; hand-written files (conventions, topic files) survive regeneration.

## Area conventions (table of contents)

- [CLI conventions](cli/CONVENTIONS.md) — `docs/cli` mirrors the `gcloud` command tree 1:1.
- [IAM conventions](iam/CONVENTIONS.md) — `docs/iam` covers the IAM bounded context; it references the roles and permissions sub-area conventions.
