# Services

## Enable

### IAM
```shell
gcloud services enable iam.googleapis.com --project=test-go-builder-authority --quiet
```

### Secret Store
```shell
gcloud services enable sts.googleapis.com --project=test-go-builder-authority --quiet
```

### Artifact Registry
```shell
gcloud services enable artifactregistry.googleapis.com --project=test-go-builder-authority --quiet
```

### Cloud Resource Manager
```shell
gcloud services enable cloudresourcemanager.googleapis.com --project=test-go-builder-authority --quiet
```

### Logging
```shell
gcloud services enable logging.googleapis.com --project=test-go-builder-authority --quiet
```

### Org Policy
```shell
gcloud services enable orgpolicy.googleapis.com --project=test-go-builder-authority --quiet
```

### Cloud KMS
```shell
gcloud services enable cloudkms.googleapis.com --project=test-go-builder-authority --quiet
```

### Access Context Manager
```shell
gcloud services enable accesscontextmanager.googleapis.com --project=test-go-builder-authority --quiet
```

- [Google Cloud Console: accesscontextmanager.googleapis.com](https://console.cloud.google.com/apis/library/accesscontextmanager.googleapis.com?project=test-software-dep-control)

### Cloud Run
```shell
gcloud services enable run.googleapis.com --project=test-software-dep-control --quiet
```

## Architectural explanation

`gcloud services enable` activates one API service on the target project through Service Usage; the caller needs `serviceusage.services.enable` (for example via a time-boxed `roles/serviceusage.serviceUsageAdmin` grant). The activation is asynchronous on the platform side — freshly enabled APIs and their service agents can take a few minutes to propagate, so the first dependent operation may fail transiently and is retried after a short wait. The read-back half is [list](../list/overview.md): the enabled service must appear there before dependent resources are created.

