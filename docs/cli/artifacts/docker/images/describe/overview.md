# artifacts docker images describe

Read one image of an Artifact Registry docker repository, including its digest.

## Usage

```shell
gcloud artifacts docker images describe <REGION>-docker.pkg.dev/<PROJECT_ID>/<REPOSITORY_NAME>/<IMAGE_NAME>:<TAG> --project=<PROJECT_ID> --format="value(image_summary.digest)"
```

## Architectural explanation

The `--format="value(image_summary.digest)"` projection reduces the answer to the registry-side content digest of the tagged image. This is the fail-closed read-back half of every delivery: the digest printed by `docker push` must equal the digest the registry reports, and a promotion must preserve the digest across registries. A mismatch fails the delivery closed; an equality is the proof that the content addressed locally is the content stored remotely.

## Verified example

```shell
gcloud artifacts docker images describe europe-west3-docker.pkg.dev/test-software-dep-control/staging-controller-images/dependency-intake-controller:<COMMIT_SHA> --project=test-software-dep-control --format="value(image_summary.digest)"
```

Proven output shape:

```text
sha256:<DIGEST>
```
