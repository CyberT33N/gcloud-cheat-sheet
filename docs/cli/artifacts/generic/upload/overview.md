# upload

[INTENT: REFERENCE]

Upload a file to a Generic Artifact Registry repository:

```shell
gcloud artifacts generic upload --project=test-software-dep-evidence --location=europe-west3 --repository=go-dependencies-evidence --package=tooling --version=osv-scanner --source="C:\path\to\osv-scanner_linux_amd64@sha256-<hex>" --destination-path="v2.5.1"
```

## Architecture

- The object path in the repository is composed as `<package>/<version>/<destination-path>/<source-file-name>`: `--destination-path` is a folder prefix only, and the uploaded object always carries the source file's base name. To land an object at an exact governed coordinate, the local staging file itself carries the declared object name and `--destination-path` carries only the folder part.
- A version cannot be overwritten: different content under an existing file name is refused, so a content change is always uploaded as a new object under its own content digest (append-only by platform behavior).
- Prove every upload by read-back: download the object with the documented `download` form into a fresh directory and verify the content digest against the bound pin — the transfer output alone is never the proof.

## Troubleshooting

- `INVALID_ARGUMENT: filename must start with a letter or number, end with a letter or number and only contain letters, numbers, and the following characters (- _ . ~ @,/)`: the destination path or file name carries a character outside the platform alphabet. Notably the `:` of the canonical digest reference form `sha256:<hex>` is not storable; the governed stored-name form writes the digest as `sha256-<hex>`.
- The upload requires a data-plane role carrying `artifactregistry.repositories.uploadArtifacts` on the repository (proven: `roles/artifactregistry.writer` carries it); the IAM policy management around it follows the bounded wrapper form documented in the [IAM policy binding](../repositories/iam-policy-binding.md) card.
