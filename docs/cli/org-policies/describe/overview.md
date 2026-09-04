# org-policies describe

Describe the organization policy for one constraint on a project, folder, or organization — optionally the effective (inherited) form.

## Usage

```shell
gcloud org-policies describe <CONSTRAINT> --project=<PROJECT_ID> --effective
```

## Architectural explanation

The plain form reads the policy object set directly on the target; `--effective` reads the evaluated policy after hierarchy inheritance and is the correct preflight before any enforcement change. The call bills against the consumer project: `--project` sets both the target and the consumer, so on a hardened zone without the `orgpolicy.googleapis.com` API the read fails closed with `SERVICE_DISABLED` once a policy object exists there — route the consumer explicitly with `--billing-project=<PROJECT_WITH_THE_API>` to keep the target and the billing surface separate. The write path (`set-policy` without `--project`) reads its consumer from the ambient default project, which is why a write can succeed while the same-zone read requires the routing form.

## Verified example

```shell
gcloud org-policies describe run.allowedVPCEgress --project=test-software-dep-evidence --billing-project=test-software-dep-control --effective
```

Proven answer form for a list constraint:

```text
name: projects/xxxxxxxxxxxx/policies/run.allowedVPCEgress
spec:
  rules:
  - values:
      allowedValues:
      - all-traffic
```

An effective answer of `allowAll: true` proves the unrestricted default state.
