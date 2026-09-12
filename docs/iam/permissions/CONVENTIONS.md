# IAM Permissions Conventions

Binding rules for `docs/iam/permissions`, the central IAM permission catalog. Parent conventions: [IAM conventions](../CONVENTIONS.md).

## Architecture rationale (why a central catalog, and why here)

- **A permission is a global entity.** Its identity is its name; its meaning is identical in every context. The IAM dataset proves the multiplication: 197,357 role→permission assignments reduce to 13,850 unique permissions — a repetition factor of 14.25. Documenting permissions per role would store the same truth ~14 times and guarantee drift; the central catalog documents each permission exactly once.
- **Location:** the catalog lives at `docs/iam/permissions/` because IAM is the owning product bounded context, and `permissions/` sits as a sibling of `roles/` because Permission and Role are peer entities of that context. Role pages reference the catalog; the catalog never absorbs role definitions.
- **Two read models of one relation:** the catalog answers "which roles grant this permission?" through the reverse index on every leaf page; the roles area answers "what does this role grant?" through its assignment pages. Both are regenerated projections of the same dataset — neither is a hand-maintained copy.
- **Why the namespace mirror:** permission names are already a hierarchy (`<service>.<resource>.<verb>` or the DNS form `<service.dns.name>/<resource>.<verb>`). Mirroring that hierarchy into folders makes every permission group addressable and keeps every page small and navigable.
- **Verbs never get folders:** the verb (the end theme, for example `get`, `list`, `getIamPolicy`) has no independent content; it is documented as an entry of its resource group's page. A folder per verb would produce tens of thousands of near-empty files with zero information gain.

## Structure mirror

- The area mirrors the global IAM permission namespace 1:1. Each permission exists here exactly once; role pages under `docs/iam/roles` link into this catalog.
- Each dot-separated segment of the permission name is exactly one folder level, nested down to the resource group. In the DNS form, the service DNS name is exactly one folder, dots preserved (for example `iam.googleapis.com/workforcePoolProviderScimUsers/overview.md`).
- Folder names equal the official segments byte-exactly, including camelCase and dots inside DNS-form service folders. They are tool-fixed identifiers and are never restyled.
- Segments that differ only by case (for example `httpFilters` vs `httpfilters`) share one folder, because common filesystems cannot hold both; the permission entries inside remain byte-exact.

## Page anatomy

- Intermediate folders carry an `overview.md` child-area index (child areas, leaf-group and permission counts).
- Leaf folders (resource groups) carry an `overview.md` with one section per permission: the exact permission name, the count of roles granting it, and the reverse index of those roles linking back to the role pages.
- Optional hand-written topic files (for example `troubleshooting.md`, `notes.md`): created only when verified content exists, named in kebab-case. The generator links them automatically in a `## Topics` section of the group's page.

## Generated vs. hand-written surfaces

- `overview.md` files are generator-owned: regenerated from the IAM API dataset, never hand-edited.
- All other files (this `CONVENTIONS.md`, topic files) are hand-written and survive regeneration: the generator preserves every non-generated file across a clean rebuild.

## Data source and completeness

- The permission universe is derived from the union of all role permission sets returned by the IAM API (`roles.list`, `view=FULL`), cross-checked against the official IAM documentation.
- Completeness is binary: every permission present in that union is documented exactly once; nothing else is documented.
- Permission-level facts that the API does not publish (for example human-readable permission descriptions) are not paraphrased or invented; they are added only when an authoritative source provides them.

## Lifecycle procedures

- **Regenerate:** same path as the roles area — refresh the dataset, rerun the generator, then run the independent verifier.
- **Add permission-topic content:** create a kebab-case topic file beside the group's `overview.md`; the next regeneration links it automatically.
- **New permission in the API:** covered automatically by the next regeneration; no manual folder creation.
