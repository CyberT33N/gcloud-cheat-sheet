# Components


## Update
```shell
gcloud components update --quiet 2>&1
```


---

## List
```shell
gcloud components list --filter="id=beta" --format="value(id,state.name)" 2>&1
```

---

## Install

### Beta
```shell
$env:CLOUDSDK_PYTHON = (& "$env:LOCALAPPDATA\Google\Cloud SDK\google-cloud-sdk\bin\gcloud.cmd" components copy-bundled-python 2>&1 | Select-Object -Last 1).Trim() ; Write-Output "CLOUDSDK_PYTHON=$env:CLOUDSDK_PYTHON" ; gcloud components install beta --quiet 2>&1 | Select-Object -Last 6
```