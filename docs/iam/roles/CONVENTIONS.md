# IAM Roles Conventions

Binding rules for `docs/iam/roles`, the IAM roles reference area. Parent conventions: [IAM conventions](../CONVENTIONS.md).

## Architecture rationale (why folder-based set assignment)

- **A role is its permission set.** The primary question a cheat sheet answers for a role is "what does this role grant?". The assignment (role → permission) is role-owned truth and must be materialized per role — it cannot move into the central catalog without inverting the model.
- **Role assignments differ — that is the architectural reason for the per-role `permissions/` folders.** Measured against the IAM API dataset: `roles/viewer` grants 6,130 permissions, `roles/reader` 6,147, `roles/editor` 12,086, `roles/writer` 12,122, `roles/owner` 13,702, `roles/admin` 13,767; 94.8 % of all 2,396 role sets are globally unique. Because the sets differ, every role materializes its own assignment. If all sets were identical, a single shared page would be correct — they are not.
- **Folder-based decomposition:** monolithic permission lists reached 10,000+ lines per role, which breaks re-anchoring, search, and editing. The assignment is therefore decomposed along the domain structure — one `permissions/<service>/overview.md` per service the role grants permissions in. The verb level (`get`, `list`, …) never gets its own folder: verbs are end themes listed on their resource group's page in the central catalog.
- **Re-reference, not duplication:** every permission listed on an assignment page links to its canonical page in the [central permission catalog](../permissions/overview.md). No permission semantics are duplicated in the roles area; the name in the list is a membership reference (foreign key), the meaning lives in the catalog (referenced row).
- **Invariant — no (role × permission) prose exists:** in the IAM model, membership is binary and permissions are context-free; IAM conditions attach to bindings, not to role definitions. Content that looks role-and-permission-specific always decomposes into permission-level content (central catalog) plus role-level content (topic file in the role folder root). Therefore the `permissions/` subtrees are generated projections forever, and no hand-written content ever lives inside them.
- **Family templates were evaluated and rejected:** 94.8 % of role sets are unique, the remaining duplicate sets are coincidental snapshots (or empty sets), and the documented inclusion chains (`viewer ⊂ editor ⊂ owner`, `reader ⊂ writer ⊂ admin`) are prose semantics, not machine relations. A template layer would elevate coincidence to structure and break when Google diverges the sets.

## Structure mirror

- The area mirrors the official IAM roles documentation structure 1:1: `basic/`, `predefined/`, `custom/`.
- `basic/` contains the six basic roles named by the official roles overview: the legacy basic roles `owner`, `editor`, `viewer` and the current basic roles `admin`, `writer`, `reader`.
- `predefined/` mirrors the official role ID hierarchy `roles/SERVICE.IDENTIFIER`: each dot-separated segment of the role ID is exactly one folder level, nested down to the last segment (for example `roles/compute.instanceAdmin.v1` → `predefined/compute/instanceAdmin/v1/overview.md`).
- Folder names equal the official role ID segments byte-exactly, including camelCase (for example `instanceAdmin`). They are tool-fixed identifiers and are never restyled.
- `custom/` is a concept area: custom roles are user-defined and have no fixed instances, so no role pages exist there.

## Role folder anatomy

Every role folder contains:

- `overview.md` — the generated role page: official description, role details (ID, title, type, launch stage, permission count), the per-service permission summary table, the verified `gcloud iam roles describe` invocation, and official documentation links.
- `permissions/<service>/overview.md` — generated assignment pages, one per service the role grants permissions in. Each lists exactly the permissions this role grants on that service and links every permission to its canonical page in the central permission catalog.
- Optional hand-written topic files (for example `troubleshooting.md`, `dependencies.md`, `incompatible-roles.md`, `details.md`): created only when verified content exists, named in kebab-case after their domain topic. The generator links them automatically in a `## Topics` section of the role page.

## Generated vs. hand-written surfaces

- `overview.md` files and `.git-keep` placeholders are generator-owned: they are regenerated from the IAM API dataset and are never hand-edited.
- All other files (this `CONVENTIONS.md`, topic files) are hand-written and survive regeneration: the generator preserves every non-generated file across a clean rebuild.
- Intermediate folders that exist only as path segments of a deeper role (no role of their own) carry an empty `.git-keep`.

## Data source and completeness

- The single source of truth for role data is the IAM API (`roles.list` with `view=FULL`, plus `roles.get` for basic roles), executed with the locally installed Google Cloud SDK and cross-checked against the official IAM documentation.
- Completeness is binary: every role returned by the API is documented; nothing else is documented. Roles or fields the API does not publish are marked factually, never invented.
- Launch stages (`GA`, `BETA`, `DEPRECATED`) are rendered exactly as the API reports them.

## Lifecycle procedures

- **Regenerate (default maintenance path):** refresh the dataset through `roles.list` (`view=FULL`) and `roles.get`, rerun the generator, then run the independent verifier (assignment coverage, central coverage, reverse-index consistency, link resolution). Never hand-edit generated pages; fix the generator instead.
- **Add role-topic content:** create a kebab-case topic file beside the role's `overview.md`; the next regeneration links it automatically. Topic content must be verified against the official documentation or the programmatic surface before it is written.
- **Edit conventions:** edit the area `CONVENTIONS.md` files by hand; they are hand-written surfaces and survive regeneration.
- **New role or permission in the API:** covered automatically by the next regeneration; no manual folder creation.
