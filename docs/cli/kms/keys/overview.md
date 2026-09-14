# KMS

## Keys

- [create](create/overview.md)
- [describe](describe/overview.md)
- [list](list/overview.md)
- [add-iam-policy-binding](add-iam-policy-binding/overview.md)
- [get-iam-policy](get-iam-policy/overview.md)
- [remove-iam-policy-binding](remove-iam-policy-binding/overview.md)

### Describe (projection form)

```shell
gcloud kms keys describe dep-evidence-signing --project=test-software-dep-control --location=europe-west3 --keyring=dep-control --format="value(purpose,versionTemplate.algorithm)"
```
