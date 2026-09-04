# Organizations Policies

## List
```shell
gcloud org-policies list --organization=xxxxxxxxxxxx --format="value(constraint)" 2>&1
```

## Set Policy
```shell
gcloud org-policies set-policy "C:\Users\test\AppData\Local\Temp\org-policies\storage-publicAccessPrevention.yaml" 2>&1
```

E.g.
```yml
name: organizations/xxxxxxxxxxxxx/policies/storage.publicAccessPrevention
spec:
  rules:
  - enforce: true
```

## Set Policy (list constraint on a project)

```shell
gcloud org-policies set-policy "C:\Users\test\AppData\Local\Temp\org-policies\run-allowedVPCEgress.yaml"
```

```yml
name: projects/xxxxxxxxxxxx/policies/run.allowedVPCEgress
spec:
  rules:
  - values:
      allowedValues:
      - all-traffic
```

Architectural explanation: a list constraint carries `values.allowedValues` instead of the boolean `enforce`. The policy name binds the project NUMBER, not the project ID. `set-policy` replaces the policy for the constraint on that resource and reads its consumer (billing) project from the ambient default — not from the file — so the write succeeds as long as the ambient project carries the `orgpolicy.googleapis.com` API, even when the target project does not. The read-back runs over [describe](describe/overview.md) with `--effective`; on a target without the API the read is routed through `--billing-project`.