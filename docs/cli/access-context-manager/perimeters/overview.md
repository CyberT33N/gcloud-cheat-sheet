# Access Context Manager

## perimeters





### create
- Note: there can be a waiting time (propagation window).

```shell
gcloud access-context-manager perimeters create dependency_authority --title="Dependency Authority" --policy=622707530139 "--resources=projects/xxxxxxxxxxx,projects/xxxxxxxxxxxxx,projects/xxxxxxxxxxxx,projects/xxxxxxxxxxxxxx,projects/xxxxxxxxxxxxxx" "--restricted-services=artifactregistry.googleapis.com,storage.googleapis.com,cloudkms.googleapis.com,logging.googleapis.com" --ingress-policies="C:\Users\test\AppData\Local\Temp\vpc-sc\ingress-admin.yaml" 2>&1 | Select-Object -Last 4 ; Write-Output "perimeter create exit=$LASTEXITCODE"
```

ingress-admin.yaml
```yaml
# VPC-SC ingress rule: organization operator channel for admin@test.software.
# ingressTo.resources must be explicitly "*" - omitted means no resource matches.
- ingressFrom:
    identities:
      - user:admin@test.software
    sources:
      - accessLevel: "*"
  ingressTo:
    resources:
      - "*"
    operations:
      - serviceName: "*"

```

---

### describe
```shell
gcloud access-context-manager perimeters describe dependency_authority --policy=xxxxxxxxxxxx --format="yaml(status.resources,status.restrictedServices,status.ingressPolicies,spec)" 2>&1 
```


---

### Update
- Note: there can be a waiting time (propagation window).

```shell
gcloud access-context-manager perimeters update dependency_authority --policy=xxxxxxxxxxxxxx --set-ingress-policies="C:\Users\test\AppData\Local\Temp\vpc-sc\ingress-admin.yaml" 2>&1 
```

### Update semantics and method selectors

`--set-ingress-policies` replaces the whole ingress set of the perimeter — the file must carry every rule that must remain (for example the administration channel) plus the new rule; a file holding only the new rule drops the existing ones. The read-back over `describe` must prove the full intended rule set.

A `methodSelectors` entry accepts `method` or `permission`. The permission form is rejected for Cloud Logging (`PERMISSION 'logging.logEntries.list' is not supported in logging.googleapis.com`); the restrictable form is the method `LoggingServiceV2.ListLogEntries` (see the supported service method restrictions). The platform validates fail-closed: an unsupported selector is rejected without changing the perimeter.
