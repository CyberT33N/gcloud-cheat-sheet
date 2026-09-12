# artifacts docker images delete

Delete one container image — by digest or by tag — from an Artifact Registry docker repository.

## Usage

Untagged digest form (deletes exactly one content digest):

```shell
gcloud artifacts docker images delete <REGION>-docker.pkg.dev/<PROJECT_ID>/<REPOSITORY_NAME>/<IMAGE_NAME>@sha256:<DIGEST> --project=<PROJECT_ID> --quiet
```

Tagged digest form (deletes the digest and all of its tags):

```shell
gcloud artifacts docker images delete <REGION>-docker.pkg.dev/<PROJECT_ID>/<REPOSITORY_NAME>/<IMAGE_NAME>@sha256:<DIGEST> --project=<PROJECT_ID> --delete-tags --quiet
```

## Architectural explanation

The digest form deletes exactly one content digest; the tag form deletes that tag and the digest it points to. The deletion is a long-running operation: the command issues the delete request and then waits for the operation to complete — the synchronous default is the proof-friendly form, while `--async` returns at request time and is never a completion proof. `--quiet` is the non-interactive form (the default behavior prompts for confirmation, which blocks unattended execution).

Three proven ordering and failure facts of this surface:

- **Tagged digests refuse a plain delete.** Deleting an image by digest while the digest is still tagged fails closed; `--delete-tags` deletes the digest and its tags together.
- **Parent before child.** The platform refuses to delete a child manifest while a parent index still references it: the delete fails closed with `failed precondition manifest has referenced parents`. When cleaning up an index-carried image set, delete the tagged index first, then the untagged child manifests — never the reverse order.
- **The wait result is not the arbiter.** A `PERMISSION_DENIED` while *waiting* on an already issued operation can still mean the deletion completed server-side. A single call's exit code is never the deletion proof: the re-run inventory (`artifacts docker images list`) is the only arbiter of what is actually gone.

## Verified example

```shell
gcloud artifacts docker images delete europe-west3-docker.pkg.dev/test-software-dep-control/staging-controller-images/dependency-intake-controller@sha256:<DIGEST> --project=test-software-dep-control --delete-tags --quiet
```

Proven result shape:

```text
Digests:
- europe-west3-docker.pkg.dev/test-software-dep-control/staging-controller-images/dependency-intake-controller@sha256:<DIGEST>

Tags:
- europe-west3-docker.pkg.dev/test-software-dep-control/staging-controller-images/dependency-intake-controller:<TAG>
Delete request issued.
Waiting for operation [projects/<PROJECT_ID>/locations/europe-west3/operations/<OPERATION_ID>] to complete...
......done.
```
