# list

[INTENT: REFERENCE]

List the Artifact Registry packages in a repository:

```shell
gcloud artifacts packages list --repository=go-dependencies-evidence --location=europe-west3 --project=test-software-dep-evidence
```

## Architecture

- The inventory form of a repository: it proves which package coordinates exist — and before a governed fill it proves that the intended target coordinates are still absent (append-only discipline).
- The output carries the package name plus create and update times; `--filter` and `--limit` narrow larger inventories (see the command help).
- The caller needs a role carrying `artifactregistry.packages.list` on the repository (proven: `roles/artifactregistry.writer` carries it).
