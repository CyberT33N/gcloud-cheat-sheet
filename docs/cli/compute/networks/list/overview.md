# compute networks list

List the VPC networks of a project.

## Usage

```shell
gcloud compute networks list --project=<PROJECT_ID> --format="value(name)"
```

## Architectural explanation

The name-only projection is the scriptable set proof: the answer enumerates every network of the project, so an expected-absence proof (a network that must not exist) and an expected-presence proof both reduce to reading the list. This is also the read-only state proof after an aborted or rejected tool execution — prove first that nothing was created before any retry.

## Verified example

```shell
gcloud compute networks list --project=test-software-dep-intake --format="value(name)"
```
