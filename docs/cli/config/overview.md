# Config

## Get value

### Account
```shell
gcloud config get-value account
```

### Project
```shell
gcloud config get-value project
```

Architectural explanation: reads the active configuration's default project — the implicit target and quota-billing container of every call that does not pass `--project` explicitly. The preflight pair `gcloud auth list` (who acts) plus `gcloud config get-value project` (where it acts by default) binds the execution context before any mutation; mutations themselves always carry an explicit `--project`.


---

## Set

### Account
```shell
gcloud config set account xxxxxxxxxxxxx@gmail.com --quiet
```
