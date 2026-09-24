# auth application-default set-quota-project

Update or add the quota project in the application default credentials (ADC).

## Usage

```shell
gcloud auth application-default set-quota-project <PROJECT_ID>
```

## Architectural explanation

Writes the quota project into the local ADC file so that Google client libraries can attribute quota and billing. The caller must hold `serviceusage.services.use` on that project (carried for example by `roles/serviceusage.serviceUsageConsumer`). The binding is a local credential-file change, not a cloud mutation.

Important boundary proven against the pinned Google provider v7.44.0: writing the quota project into the ADC file is necessary but **not sufficient** for the OpenTofu/Terraform Google provider. The provider sends the `X-Goog-User-Project` header only when `user_project_override = true` **and** a billing project is set — otherwise API calls that require a quota project (for example `orgpolicy.googleapis.com`) fail with `403 SERVICE_DISABLED` attributed to the gcloud default consumer project. The complete provider-side form is the process environment of the engine run:

```powershell
cmd /c 'set "USER_PROJECT_OVERRIDE=true" && set "GOOGLE_BILLING_PROJECT=<PROJECT_ID>" && set "GOOGLE_CLOUD_QUOTA_PROJECT=<PROJECT_ID>" && tofu plan -input=false -no-color -var-file=window.tfvars'
```

## Verified example

```shell
gcloud auth application-default set-quota-project test-software-dep-control
```

Proven result: `Quota project "test-software-dep-control" was added to ADC`. The subsequent engine plan still failed on the org-policy reads until the provider-side override pair above was bound — then the plan completed (exit 2, changes proposed).
