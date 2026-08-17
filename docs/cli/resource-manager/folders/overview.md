# Resource Manager

## Folders

### List
```shell
gcloud resource-manager folders list --organization=xxxxxxxxxxxxxx --format="value(name,displayName,lifecycleState)"
```

### Descrfibe
```shell
gcloud resource-manager folders describe xxxxxxxxxxxxxx --format="value(name,displayName,lifecycleState,parent)" ; gcloud organizations get-iam-policy xxxxxxxxxxxxxxxxxxxx --flatten="bindings[].members" --filter="bindings.members:user:admin@t33n.software" --format="value(bindings.role)"
```

### Create
```shell
gcloud resource-manager folders create --display-name=dependency-authority --organization=xxxxxxxxxxxx 2>&1
```
