# projects list

List the Google Cloud projects accessible by the active account.

## Usage

```shell
gcloud projects list --format="value(projectId,projectNumber,lifecycleState)"
```

## Architectural explanation

Lists every active project the active account can access (Owner, Editor,
Browser or Viewer), one line per project under the given projection. This is
the baseline inventory read before binding project-scoped values: it proves
which projects actually exist live, their immutable numbers and their
lifecycle state — a project reference is never bound from memory. Projects
that are deleted or pending deletion are excluded by default; the
`--filter='lifecycleState:DELETE_REQUESTED'` form lists those.

## Verified example

```shell
gcloud projects list --format="value(projectId,projectNumber,lifecycleState)"
```

Proven result: the organization inventory — the anchor project
`test-software-org-anchor` (ACTIVE) plus the five trust-zone projects
`test-software-dep-{control,intake,quarantine,approved,evidence}`, all
ACTIVE (verified during the foundation state-home binding recognition).
