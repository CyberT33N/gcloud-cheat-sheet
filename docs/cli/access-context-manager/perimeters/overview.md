# Access Context Manager

## perimeters

### create

```shell
gcloud access-context-manager perimeters create dependency_authority --title="Dependency Authority" --policy=622707530139 "--resources=projects/xxxxxxxxxxx,projects/xxxxxxxxxxxxx,projects/xxxxxxxxxxxx,projects/xxxxxxxxxxxxxx,projects/xxxxxxxxxxxxxx" "--restricted-services=artifactregistry.googleapis.com,storage.googleapis.com,cloudkms.googleapis.com,logging.googleapis.com" --ingress-policies="C:\Users\denni\AppData\Local\Temp\vpc-sc\ingress-admin.yaml" 2>&1 | Select-Object -Last 4 ; Write-Output "perimeter create exit=$LASTEXITCODE"
```

ingress-admin.yaml
```yaml
# VPC-SC ingress rule: organization operator channel for admin@test.software.
# Identity-bound administration path into the dependency-authority perimeter;
# no workload identity receives ingress (workloads federate via WIF inside).
- ingressFrom:
    identities:
      - user:admin@test.software
    sources:
      - accessLevel: "*"
  ingressTo:
    operations:
      - serviceName: "*"

```

---

### describe
```shell
gcloud access-context-manager perimeters describe dependency_authority --policy=xxxxxxxxxxxx --format="yaml(status.resources,status.restrictedServices,status.ingressPolicies,spec)" 2>&1 
```