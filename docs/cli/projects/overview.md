# Projects


## Create

### MUltiple projects
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== create t33n-software-dep-$z =="; gcloud projects create "t33n-software-dep-$z" --name="t33n-software-dep-$z" --labels="boundary=dependency-authority,zone=$z" --format="value(projectId,lifecycleState)" }
```

## List
```shell
gcloud projects list
```

## Describe
```shell
gcloud projects describe
```