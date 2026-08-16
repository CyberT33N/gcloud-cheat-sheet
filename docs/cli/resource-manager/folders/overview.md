# Resource Manager

## Folders

### List
```shell
gcloud resource-manager folders list --organization=xxxxxxxxxxxxxx --format="value(name,displayName,lifecycleState)"
```


### Create
```shell
gcloud resource-manager folders create --display-name=dependency-authority --organization=xxxxxxxxxxxx 2>&1
```
