# delete

[INTENT: REFERENCE]

Delete one Artifact Registry file by its composed identity `<package>:<version>:<path>`:

```shell
gcloud artifacts files delete "tooling:osv-scanner:v2.5.1/osv-scanner_linux_amd64@sha256-<hex>" --location=europe-west3 --repository=go-dependencies-evidence --project=test-software-dep-evidence
```

## Architecture

- The delete targets exactly one file identity; read the current inventory first with `files list` and delete only an identity proven to exist — never a guessed path.
- The command works only on Generic repositories and requires a role carrying the file delete permission on the repository (proven: [`roles/artifactregistry.admin`](../../../../iam/roles/predefined/artifactregistry/admin/overview.md) carries it; the data-plane [`roles/artifactregistry.writer`](../../../../iam/roles/predefined/artifactregistry/writer/overview.md) does not) — a governed cleanup therefore runs under the bounded admin wrapper, never under the standing data-plane grant.
- The command asks for confirmation interactively; in a non-interactive run the default answer continues. Prove the deletion by an independent `files list` read-back: the identity must be absent and every other object unchanged.
