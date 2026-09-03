# run jobs list

List the Cloud Run jobs of a project in one region.

## Usage

```shell
gcloud run jobs list --project=<PROJECT_ID> --region=<REGION> --format="value(name)"
```

## Architectural explanation

The list is the topology proof: which jobs exist under their canonical names. It is also the lightweight permission pre-verify after an IAM change — a caller with a fresh grant proves the propagation with this simpler read before running the target operation.

## Verified example

```shell
gcloud run jobs list --project=test-software-dep-intake --region=europe-west3 --format="value(name)"
```
