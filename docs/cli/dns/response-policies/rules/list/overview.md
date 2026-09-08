# dns response-policies rules list

List all rules of a Cloud DNS response policy.

## Usage

```shell
gcloud dns response-policies rules list <POLICY_NAME> --project=<PROJECT_ID> --format="json(ruleName,dnsName)"
```

## Architectural explanation

The policy name is a positional argument, not a flag. The inventory is the before-and-after proof of every rule mutation: a create or delete changes exactly one rule, and only the list proves the full resulting set — a rule that was never listed is never proven present or absent. The `ruleName,dnsName` projection carries the identity and the matched DNS name of every rule; the answer content of a single rule is proven over [describe](../describe/overview.md), and the network attachment of the policy itself over [the policy describe](../../describe/overview.md).

## Verified example

```shell
gcloud dns response-policies rules list dep-intake-workload-restricted-googleapis --project=test-software-dep-intake --format="json(ruleName,dnsName)"
```
