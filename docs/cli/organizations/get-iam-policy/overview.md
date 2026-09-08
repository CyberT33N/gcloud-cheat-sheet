# organizations get-iam-policy

Read the IAM policy of an organization.

## Usage

```shell
gcloud organizations get-iam-policy <ORGANIZATION_ID> --format=json
```

## Architectural explanation

The organization IAM policy is the org-level authorization surface: it carries the standing roles of the platform operator (for example the resourcemanager, orgpolicy and accesscontextmanager roles) that every just-in-time project grant relies on. The JSON form composes with `ConvertFrom-Json` in PowerShell for exact assertions — filtering `bindings` on a member proves which org-level roles that member holds. This is the read that proves the operator's granting capability before any governed mutation.

## Verified example

```powershell
$org = gcloud organizations get-iam-policy <ORGANIZATION_ID> --format=json | ConvertFrom-Json
$org.bindings | Where-Object { $_.members -contains 'user:admin@test.software' } | ForEach-Object { $_.role }
```
