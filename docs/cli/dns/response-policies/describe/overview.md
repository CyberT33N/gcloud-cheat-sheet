# dns response-policies describe

Read one Cloud DNS response policy.

## Usage

```shell
gcloud dns response-policies describe <POLICY_NAME> --project=<PROJECT_ID> --format="json(responsePolicyName,networks)"
```

## Architectural explanation

The `networks` projection proves which VPC the policy is bound to — the binding is the effective property, because a response policy without a network attachment rewrites nothing.

## Verified example

```shell
gcloud dns response-policies describe dep-intake-workload-restricted-googleapis --project=test-software-dep-intake --format="json(responsePolicyName,networks)"
```
