# Projects


## Create

### Multiple projects
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== create test-software-dep-$z =="; gcloud projects create "test-software-dep-$z" --name="test-software-dep-$z" --labels="boundary=dependency-authority,zone=$z" --format="value(projectId,lifecycleState)" }
```

