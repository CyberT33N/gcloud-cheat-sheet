# Artifacts

## Docker

### images 

#### Copy
```shell
$src = "europe-west3-docker.pkg.dev/test-software-dep-control/staging-controller-images/dependency-intake-controller@$global:STAGED_DIGEST"; $dst = "europe-west3-docker.pkg.dev/test-software-dep-control/release-controller-images/dependency-intake-controller:xxxxxxxxxxxxxxxxxxxxx"; "PROMOTE_SOURCE=$src"; gcloud artifacts docker images copy $src $dst --project=test-software-dep-control
```