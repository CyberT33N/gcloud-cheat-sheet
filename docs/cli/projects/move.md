# Projects


## Move
1. Run install beta
- [components](../components/overview.md)

2. Set correct permission
```shell
gcloud config set account test@gmail.com --quiet ; gcloud projects add-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/owner" --format=none ; Write-Output "grant-owner exit=$LASTEXITCODE" ; gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:test@gmail.com" --role="roles/owner" --format=none ; Write-Output "remove-owner exit=$LASTEXITCODE" ; Write-Output "--- remaining bindings on control:" ; gcloud projects get-iam-policy test-software-dep-control --flatten="bindings[].members" --format="value(bindings.role,bindings.members)"
```


3. Then move:
```shell
gcloud beta projects move test-software-dep-control --folder=xxxxxxxxxxxxxx --quiet 2>&1
```

`gcloud beta projects move` is broken: the implementation reads through the deprecated Resource Manager v1 API (403 for owner and admin alike, proven via debug trace). The migration succeeded via the v3 REST method `projects.move` with the same identity (admin@test.software); the access token was used only in-process and was never printed or persisted. Same operation, same governance, working transport.

Bound move preconditions (official v3 documentation): on a project without a parent, the caller additionally needs `resourcemanager.projects.setIamPolicy` and `resourcemanager.projects.update` — solved via `roles/resourcemanager.projectIamAdmin` + `roles/editor` for the org admin (plus `roles/logging.configWriter` for the sinks). The previously suspected domain restriction was not the blocker; it also did not block the logging service agents.


Alternative via REST:
```shell
gcloud config set account admin@test.software --quiet ; $token = (gcloud auth print-access-token) ; $headers = @{ Authorization = "Bearer $token" } ; $body = '{"destinationParent":"folders/xxxxxxxxxxxxxx"}' ; try { $resp = Invoke-RestMethod -Method Post -Uri "https://cloudresourcemanager.googleapis.com/v3/projects/test-software-dep-control:move" -Headers $headers -Body $body -ContentType "application/json" ; Write-Output ("MOVE-OK: " + ($resp | ConvertTo-Json -Depth 5 -Compress)) } catch { $r = $_.Exception.Response ; $sr = New-Object System.IO.StreamReader($r.GetResponseStream()) ; Write-Output ("STATUS: " + [int]$r.StatusCode) ; Write-Output ("BODY: " + $sr.ReadToEnd()) } ; Start-Sleep -Seconds 10 ; gcloud projects describe test-software-dep-control --format="value(projectId,lifecycleState,parent.type,parent.id)"
```

