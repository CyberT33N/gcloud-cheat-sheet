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

---



### test-iam-permissions
```shell
gcloud resource-manager folders test-iam-permissions xxxxxxxxxxxxxxxxxxxxx --permissions=resourcemanager.projects.move --format="value(permissions)" 2>&1 
```
