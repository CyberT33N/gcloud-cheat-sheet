# Projects


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

gcloud beta projects move ist gebrochen: Die Implementierung liest über die stillgelegte Resource-Manager-v1-API (403 für Owner und Admin gleichermaßen, bewiesen per Debug-Trace). Die Migration lief über die v3-REST-Methode projects.move mit derselben Identität (admin@test.software); das Zugriffstoken wurde nur prozessintern verwendet und nirgends ausgegeben oder persistiert. Gleiche Operation, gleiche Governance, funktionierender Transport.

Gebundene Move-Vorbedingungen (offizielle v3-Dokumentation): auf einem parentlosen Projekt braucht der Aufrufer zusätzlich resourcemanager.projects.setIamPolicy und resourcemanager.projects.update — gelöst über roles/resourcemanager.projectIamAdmin + roles/editor für den Org-Admin (plus roles/logging.configWriter für die Sinks). Die zuvor vermutete Domain-Restriction war nicht der Blocker; sie blockierte auch die Logging-Service-Agents nicht.


Alternative via REST:
```shell
gcloud config set account admin@test.software --quiet ; $token = (gcloud auth print-access-token) ; $headers = @{ Authorization = "Bearer $token" } ; $body = '{"destinationParent":"folders/xxxxxxxxxxxxxx"}' ; try { $resp = Invoke-RestMethod -Method Post -Uri "https://cloudresourcemanager.googleapis.com/v3/projects/test-software-dep-control:move" -Headers $headers -Body $body -ContentType "application/json" ; Write-Output ("MOVE-OK: " + ($resp | ConvertTo-Json -Depth 5 -Compress)) } catch { $r = $_.Exception.Response ; $sr = New-Object System.IO.StreamReader($r.GetResponseStream()) ; Write-Output ("STATUS: " + [int]$r.StatusCode) ; Write-Output ("BODY: " + $sr.ReadToEnd()) } ; Start-Sleep -Seconds 10 ; gcloud projects describe test-software-dep-control --format="value(projectId,lifecycleState,parent.type,parent.id)"
```

