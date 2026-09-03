# get-iam-policy

## YAML projection

```shell
gcloud iam service-accounts get-iam-policy gba-builder-promoter@cybertest-go-builder-authority.iam.gserviceaccount.com --project=test-go-builder-authority --format="yaml(bindings)"
```

## JSON form (scriptable read-back)

```shell
gcloud iam service-accounts get-iam-policy dep-intake-fetcher@test-software-dep-intake.iam.gserviceaccount.com --project=test-software-dep-intake --format=json
```

## Architectural explanation

The read-back of the service-account IAM policy is the independent proof half of every binding change: the answer must show exactly the intended member/role pairs — and after a removal, none. The JSON form composes with `ConvertFrom-Json` in PowerShell for exact assertions; an absent `bindings` property proves the empty policy.
