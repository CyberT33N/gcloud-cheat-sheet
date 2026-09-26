# pam check-onboarding-status

Check the Privileged Access Manager (PAM) onboarding status of a project, folder, or organization.

## Usage

```shell
gcloud pam check-onboarding-status --project=<PROJECT_ID> --location=global
```

## Architectural explanation

The onboarding status reports whether the platform setup of Privileged Access Manager is complete for the resource: the organization-level PAM service agent (`service-org-<ORGANIZATION_NUMBER>@gcp-sa-pam.iam.gserviceaccount.com`) must hold `roles/privilegedaccessmanager.projectServiceAgent` on the project so that PAM can manage time-bound role bindings on it. Findings name the missing permissions and the agent; a clean answer carries no findings. This is the diagnostic surface to run before the first entitlement of a resource is created — and the proof surface after the platform setup is bound. The caller needs `privilegedaccessmanager.locations.checkOnboardingStatus` on the resource (for example via [`roles/privilegedaccessmanager.admin`](../../../iam/roles/predefined/privilegedaccessmanager/admin/overview.md)).

## Verified example

```powershell
gcloud pam check-onboarding-status --project=test-software-dep-control --location=global
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64) against a live project: after the service-agent binding was granted, the command parsed the location resource and reported no findings — the platform setup is complete. Before the binding, the same command reported the missing project permissions of the organization-level service agent by name.
