# projects describe

Show the metadata of one Google Cloud project.

## Usage

```shell
gcloud projects describe <PROJECT_ID>
```

## Architectural explanation

Prints the project metadata: the project ID, the immutable project number,
the lifecycle state, the creation time and the parent (the organization node
or a folder). This is the identity proof of a project before it is bound as
a reference: the parent placement and the lifecycle state are the evidence
that the project is the intended one — never a name similarity. The command
fails when the project does not exist or the active account has no access.

## Verified example

```shell
gcloud projects describe test-software-org-anchor
```

Proven result: `lifecycleState: ACTIVE`, `parent.type: organization` with
the organization node id, and the immutable `projectNumber` — the
organization anchor project is proven live directly under the organization
node (verified during the foundation state-home binding recognition).
