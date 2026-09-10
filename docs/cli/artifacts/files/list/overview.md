# list

[INTENT: REFERENCE]

List the Artifact Registry files in a repository, optionally narrowed to one package or one version:

```shell
gcloud artifacts files list --repository=go-dependencies-evidence --location=europe-west3 --project=test-software-dep-evidence
```

## Architecture

- The file-level inventory of a repository: every stored object with its composed identity `<package>:<version>:<path>`, its size and its owning package version — the form that proves which governed objects exist and at which exact coordinates.
- Narrow the inventory with `--package` and `--version` when the repository carries many objects (see the command help for the filter flags).
- The caller needs a role carrying `artifactregistry.files.list` on the repository (proven: `roles/artifactregistry.writer` carries it).
