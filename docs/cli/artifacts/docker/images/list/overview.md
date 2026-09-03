# artifacts docker images list

List the images of an Artifact Registry docker repository.

## Usage

```shell
gcloud artifacts docker images list <REGION>-docker.pkg.dev/<PROJECT_ID>/<REPOSITORY_NAME> --project=<PROJECT_ID>
```

## Architectural explanation

The list is the inventory proof of a registry class: an empty answer ("Listed 0 items.") proves the class was never written directly, and a present entry proves a delivery. This is the boundary proof of the promotion discipline — the release class is filled exclusively through promotion, so its inventory before a first promotion must be empty.

## Verified example

```shell
gcloud artifacts docker images list europe-west3-docker.pkg.dev/test-software-dep-control/release-controller-images --project=test-software-dep-control
```
