# Installation on Ubuntu

[INTENT: REFERENCE]

On Ubuntu, use the official APT method from Google.

## 1. Install prerequisites

```bash
sudo apt update
sudo apt install -y ca-certificates gnupg curl
```

## 2. Add the Google repository key

```bash
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg \
  | sudo gpg --dearmor -o /usr/share/keyrings/cloud.google.gpg
```

## 3. Add the Google Cloud repository

```bash
echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] https://packages.cloud.google.com/apt cloud-sdk main" \
  | sudo tee /etc/apt/sources.list.d/google-cloud-sdk.list
```

## 4. Install gcloud

```bash
sudo apt update
sudo apt install -y google-cloud-cli
```

## 5. Verify the installation

```bash
gcloud version
```

Afterwards you can sign in to Google Cloud and configure `gcloud`:

```bash
gcloud init
```

`gcloud init` walks you through authentication and the selection or creation of a project.

The official guide: [Install the Google Cloud CLI for Ubuntu](https://docs.cloud.google.com/sdk/docs/install-sdk)
