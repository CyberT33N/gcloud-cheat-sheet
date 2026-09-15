# CLI Conventions

Binding rules for `docs/cli`, the `gcloud` command reference area.

## Structure mirror

- `docs/cli` mirrors the official `gcloud` CLI command hierarchy 1:1: one folder per command group or command segment, nested down to the last subcommand.
- Folder names equal the official command tokens exactly (for example `run`, `jobs`, `describe`). They are tool-fixed identifiers and are never restyled, translated, or renamed.
- The mirror covers the GA surface and the `beta` surface (the `beta/` subtree mirrors `gcloud beta ...`).

## Files

- Every folder that has documented content carries an `overview.md`.
- Every folder without documented content carries an empty `.git-keep` placeholder. Once content is added, the `.git-keep` is removed.
- `overview.md` on a command-group level is a navigation index of its children; on a command (leaf) level it documents the command.

## Command page layout

1. `# <command path>` — the command path without the `gcloud` prefix (for example `# run jobs describe`).
2. One-sentence purpose.
3. `## Usage` — the verified boilerplate with semantic placeholders (`<PROJECT_ID>`, `<REGION>`, …).
4. `## Architectural explanation` — what the command does, why, and what the relevant flags and output fields mean.
5. `## Verified example` — a real executed invocation with its proven result.
6. Optional deep-dive sections for non-obvious behavior, failure modes, and troubleshooting findings.

## IAM role and permission references

- When added content describes roles or permissions covered by the IAM area under `docs/iam`, the owning IAM location is searched first: `docs/iam/roles/` for roles, `docs/iam/permissions/` for permissions. The location is derived from the official identifier (role ID segments, permission name segments) — never guessed.
- If the location exists, the command page references it by link. Role and permission semantics are never duplicated into `docs/cli` (single source of truth per concept).
- If the location does not exist, it is created in the IAM area before the command page is finalized — the [IAM conventions](../iam/CONVENTIONS.md) own the creation path — and then referenced by link.

## Verification

- A command is documented only after it has been executed and its result verified against the live system (100% functional proof).
- The command grammar is verified against the local `gcloud <path> --help` surface and the [official gcloud CLI reference](https://docs.cloud.google.com/sdk/gcloud/reference).
- Findings from failures or misbehavior during verification are recorded in the page (troubleshooting capture).
