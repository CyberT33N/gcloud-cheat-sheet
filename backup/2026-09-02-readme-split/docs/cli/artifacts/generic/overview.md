
Download artifacts files and check something
```shell
#!/usr/bin/env bash
set -euo pipefail

PROJECT_ID="git-governance-release-broker"
LOCATION="europe-west3"
REPOSITORY="release-broker-staging-evidence"
PACKAGE="broker-evidence"
VERSION="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OUT="$HOME/broker-evidence-${VERSION}"

mkdir -p "$OUT"

gcloud artifacts generic download \
  --project="$PROJECT_ID" \
  --location="$LOCATION" \
  --repository="$REPOSITORY" \
  --package="$PACKAGE" \
  --version="$VERSION" \
  --destination="$OUT"

count="$(find "$OUT" -maxdepth 1 -type f | wc -l)"
test "$count" -eq 22

echo "OK-Download: ${count} Evidence-Dateien heruntergeladen."



DIGEST="sha256:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
IMAGE="europe-west3-docker.pkg.dev/git-governance-release-broker/release-broker-staging-images/broker@${DIGEST}"

jq -e --arg digest "$DIGEST" --arg image "$IMAGE" '
  .subject.type == "artifact" and
  .artifact.digest == $digest and
  .artifact.reference == $image and
  .lifecycle.status == "pending"
' "$OUT/artifact.subject.json" >/dev/null

jq -e --arg digest "$DIGEST" --arg image "$IMAGE" '
  .subject.type == "deployment" and
  .subject.primary_digest == $digest and
  .lifecycle.status == "verified" and
  .lifecycle.target_lane == "staging" and
  .lifecycle.phase_references.deployed_image == $image
' "$OUT/deployment.subject.json" >/dev/null

echo "OK-Verify: Staging-Artifact und Deployment-Evidence sind korrekt gebunden."
```
