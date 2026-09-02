

# Files

## list
```shell
gcloud artifacts files list \
  --project="git-governance-release-broker" \
  --location="europe-west3" \
  --repository="release-broker-staging-evidence" \
  --format="table(name,owner,hashes)"
```

