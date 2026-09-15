# download

[INTENT: REFERENCE]

Download one file of a Generic Artifact Registry repository version:

```shell
gcloud artifacts generic download --project=test-software-dep-evidence --location=europe-west3 --repository=go-dependencies-evidence --package=osv-scanner --version=v2.5.1 --name="osv-scanner_linux_amd64@sha256-<hex>" --destination="C:\path\to\target-dir"
```

## Architecture

- `--package` and `--version` address the artifact version; `--name` selects the file within it (the exact stored file name, including any folder prefix). Without `--name` every file of the version downloads while maintaining the folder hierarchy; with `--name` the file lands directly in the destination directory.
- The stored file address is the facet form `<package>:<version>:<filename>` (see the [upload](../upload/overview.md) card); read the inventory with [files list](../files/list/overview.md) and bind the exact displayed identity — never a guessed name.
- The destination directory must exist — the command fails closed on a missing target directory before any transfer.
- The caller needs a data-plane role carrying `artifactregistry.repositories.downloadArtifacts` on the repository (proven: [`roles/artifactregistry.writer`](../../../../iam/roles/predefined/artifactregistry/writer/overview.md) carries it).
- The transfer output is never the integrity proof: verify the downloaded bytes by an independent content digest (for example sha256) against the bound pin.
