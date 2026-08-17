# Resource Manager

## Folders

### List
```shell
gcloud resource-manager folders list --organization=xxxxxxxxxxxxxx --format="value(name,displayName,lifecycleState)"
```

### Descrfibe
```shell
gcloud resource-manager folders describe xxxxxxxxxxxxxx --format="value(name,displayName,lifecycleState,parent)"; 
```

### Create
```shell
gcloud resource-manager folders create --display-name=dependency-authority --organization=xxxxxxxxxxxx 2>&1
```
