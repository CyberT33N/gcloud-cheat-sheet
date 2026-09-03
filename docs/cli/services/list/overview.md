# Services

## List

### Enabled services of a project (scriptable form)

```shell
gcloud services list --enabled --project=<PROJECT_ID> --filter="name:<API_NAME>" --format="value(name)"
```

### Architectural explanation

`gcloud services list --enabled` reads the Service Usage surface of the target project and returns the enabled API services. The `--filter="name:<API_NAME>"` predicate narrows the answer to exactly one service, and `--format="value(name)"` reduces the output to the bare resource name — the composition yields a scriptable proof: empty output means the API is not enabled, one line means it is. This is the read-back half of every API activation and the preflight check before any operation that depends on a service.

The read requires `serviceusage.services.list` on the target project (for example via a time-boxed `roles/serviceusage.serviceUsageAdmin` grant); in a hardened project without standing user roles the call fails closed with `AUTH_PERMISSION_DENIED` until such a grant exists.

### Verified example (Cloud Run API)

```shell
gcloud services list --enabled --project=test-software-dep-control --filter="name:run.googleapis.com" --format="value(name)"
```

Proven output after activation:

```text
projects/xxxxxxxxxxxx/services/run.googleapis.com
```
