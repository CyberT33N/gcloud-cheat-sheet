# projects get-iam-policy

Read the IAM policy of a project.

## Usage

```shell
gcloud projects get-iam-policy <PROJECT_ID> --format=json
```

## Architectural explanation

The project IAM policy is the project-scoped authorization surface. The JSON form composes with `ConvertFrom-Json` in PowerShell for exact assertions: filtering `bindings` on a member proves which roles that member holds — an empty answer proves the hardened state (no standing binding for that member). This is the independent read-back half of every grant and removal.

## Verified example

```powershell
$pol = gcloud projects get-iam-policy test-software-dep-control --format=json | ConvertFrom-Json
($pol.bindings | Where-Object { $_.members -contains 'user:admin@test.software' } | ForEach-Object { $_.role })
```
