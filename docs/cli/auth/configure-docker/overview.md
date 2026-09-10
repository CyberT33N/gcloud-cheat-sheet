# auth configure-docker

Register the gcloud credential helper for an Artifact Registry docker host in the local docker configuration.

## Usage

```shell
gcloud auth configure-docker <REGION>-docker.pkg.dev --quiet
```

## Architectural explanation

The command writes the local docker config only — it binds the docker client to the gcloud credential helper for the given registry host and mutates no platform state. The form is idempotent: an already registered helper answers `gcloud credential helpers already registered correctly.` and stays unchanged. This is the preflight of every image delivery: the proof that a following push or pull authenticates without a separate login. It never prints or stores a token; the helper resolves short-lived credentials from the active gcloud session at call time.

## Verified example

```shell
gcloud auth configure-docker europe-west3-docker.pkg.dev --quiet
```
