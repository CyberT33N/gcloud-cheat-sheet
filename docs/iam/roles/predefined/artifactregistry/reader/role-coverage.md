# Role coverage: `roles/artifactregistry.reader` is covered by `roles/artifactregistry.writer`

`roles/artifactregistry.reader` is fully covered by [`roles/artifactregistry.writer`](../writer/overview.md): every one of the reader's 33 permissions is included in the writer's 44. **When the Writer role is set, the Reader role is never required in addition** — a separate Reader binding is redundant, because the Writer permission set already carries the complete read capability.

## Evidence

The coverage is verified against the programmatic surface, never assumed from the role names:

```shell
gcloud iam roles describe roles/artifactregistry.reader --format="value(includedPermissions)"
gcloud iam roles describe roles/artifactregistry.writer --format="value(includedPermissions)"
```

Every entry of the reader list is present in the writer list (33 of 33), including the read anchor `artifactregistry.repositories.downloadArtifacts` in the [central permission catalog](../../../../permissions/artifactregistry/repositories/overview.md). The generated assignment pages of both roles show the same coverage: [reader](permissions/artifactregistry/overview.md), [writer](../writer/permissions/artifactregistry/overview.md).

## Related

- [`roles/artifactregistry.writer`](../writer/overview.md) — the covering role; setting it already grants every Reader permission, so never set the Reader role in addition.
