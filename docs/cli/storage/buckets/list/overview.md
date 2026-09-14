# storage buckets list

List the Cloud Storage buckets of a project.

## Usage

```shell
gcloud storage buckets list --project=<PROJECT_ID> --format="value(name)"
```

## Architectural explanation

Lists every bucket of the project, one name per line under the `value(name)` projection. This is the baseline read before a bucket creation and the cheap permission pre-verify of a storage window: it exercises `storage.buckets.list` through the same permission path the creation will use, and an empty answer proves both the working permission and the absence of any bucket — the expected pre-birth state of a state home.

## Verified example

```shell
gcloud storage buckets list --project=test-software-dep-control --format="value(name)"
```

Proven result: an empty answer — no buckets exist in the project, and no permission denial surfaces (verified in the state-home bootstrap window preflight).
