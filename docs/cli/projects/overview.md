# Projects


## Create

### Multiple projects
```shell
foreach ($z in 'control','intake','quarantine','approved','evidence') { Write-Output "== create test-software-dep-$z =="; gcloud projects create "test-software-dep-$z" --name="test-software-dep-$z" --labels="boundary=dependency-authority,zone=$z" --format="value(projectId,lifecycleState)" }
```


---

## Move
1. Run install beta
- docs\cli\components\overview.md

2. Set correct permission
```shell
gcloud config set account test@gmail.com --quiet ; gcloud projects add-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/owner" --format=none ; Write-Output "grant-owner exit=$LASTEXITCODE" ; gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:test@gmail.com" --role="roles/owner" --format=none ; Write-Output "remove-owner exit=$LASTEXITCODE" ; Write-Output "--- remaining bindings on control:" ; gcloud projects get-iam-policy test-software-dep-control --flatten="bindings[].members" --format="value(bindings.role,bindings.members)"
```


3. Then move:
```shell
gcloud beta projects move test-software-dep-control --folder=xxxxxxxxxxxxxx --quiet 2>&1
```


Alternative via REST:
```shell
gcloud config set account admin@test.software --quiet ; $token = (gcloud auth print-access-token) ; $headers = @{ Authorization = "Bearer $token" } ; $body = '{"destinationParent":"folders/xxxxxxxxxxxxxx"}' ; try { $resp = Invoke-RestMethod -Method Post -Uri "https://cloudresourcemanager.googleapis.com/v3/projects/test-software-dep-control:move" -Headers $headers -Body $body -ContentType "application/json" ; Write-Output ("MOVE-OK: " + ($resp | ConvertTo-Json -Depth 5 -Compress)) } catch { $r = $_.Exception.Response ; $sr = New-Object System.IO.StreamReader($r.GetResponseStream()) ; Write-Output ("STATUS: " + [int]$r.StatusCode) ; Write-Output ("BODY: " + $sr.ReadToEnd()) } ; Start-Sleep -Seconds 10 ; gcloud projects describe test-software-dep-control --format="value(projectId,lifecycleState,parent.type,parent.id)"
```



---

## List
```shell
gcloud projects list
```

## Describe
```shell
gcloud projects describe
```


---

## add-iam-policy-binding

### Multiple
```shell
foreach ($p in 'test-software-dep-control','test-software-dep-intake','test-software-dep-quarantine','test-software-dep-approved','test-software-dep-evidence') { Write-Output "== $p" ; gcloud projects add-iam-policy-binding $p --member="user:admin@test.software" --role="roles/resourcemanager.projectMover" --format="value(bindings.role)" --flatten="bindings" }
```


## remove-iam-policy-binding
```shell
gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:test@gmail.com" --role="roles/owner" --format=none ; Write-Output "remove-owner exit=$LASTEXITCODE"
```