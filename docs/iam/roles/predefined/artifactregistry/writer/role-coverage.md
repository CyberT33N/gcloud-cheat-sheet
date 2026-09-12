# Role coverage: `roles/artifactregistry.writer` covers `roles/artifactregistry.reader`

`roles/artifactregistry.writer` covers every permission of [`roles/artifactregistry.reader`](../reader/overview.md): the writer's 44 permissions include the reader's 33. **When the Writer role is set, the Reader role is never required in addition** — a separate Reader binding is redundant, because the Writer permission set already carries the complete read capability.

## Evidence

The coverage is verified against the programmatic surface, never assumed from the role names:

```shell
gcloud iam roles describe roles/artifactregistry.writer --format="value(includedPermissions)"
gcloud iam roles describe roles/artifactregistry.reader --format="value(includedPermissions)"
```

Every entry of the reader list is present in the writer list (33 of 33), including the read anchor `artifactregistry.repositories.downloadArtifacts` in the [central permission catalog](../../../../permissions/artifactregistry/repositories/overview.md). The generated assignment pages of both roles show the same coverage: [writer](permissions/artifactregistry/overview.md), [reader](../reader/permissions/artifactregistry/overview.md).

## Related

- [`roles/artifactregistry.reader`](../reader/overview.md) — the covered role; never set it in addition to the Writer role.
