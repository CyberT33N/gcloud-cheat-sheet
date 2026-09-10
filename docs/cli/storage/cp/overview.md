# cp

[INTENT: REFERENCE]

Copy objects between the local file system and Cloud Storage (and between cloud providers). The single-object download form:

```shell
gcloud storage cp gs://osv-vulnerabilities/Go/all.zip "C:\path\to\local\file.zip"
```

## Architecture

- The positional arguments are source then destination: a `gs://` source with a filesystem destination is a download, the reverse is an upload.
- Public objects (for example the OSV vulnerability database exports under `gs://osv-vulnerabilities/`) download without any bucket-level grant; the command still runs under the authenticated gcloud account.
- The command prints the resolved copy pair and the average throughput. The downloaded bytes are proven afterwards by an independent content digest (for example sha256) — the transfer output alone is never the integrity proof.
