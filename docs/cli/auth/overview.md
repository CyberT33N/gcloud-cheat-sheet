# Auth


## print-access-token
```shell
gcloud auth print-access-token
```


## list
```shell
gcloud auth list
```

Architectural explanation: reads the local SDK credential store and prints every stored account with the `*` marker on the account that invocations currently authenticate as. This is the first read-only preflight proof before any mutation — it proves which identity will act — and it never prints tokens. An expired session surfaces at the first API call as `Reauthentication failed. cannot prompt during non-interactive execution`; the remediation is an interactive `gcloud auth login` by the user, never a scripted credential workaround.

## configure-docker
```shell
gcloud auth configure-docker europe-west3-docker.pkg.dev --quiet
```
