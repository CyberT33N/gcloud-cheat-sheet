# storage objects list

List Cloud Storage objects.

## Usage

```shell
gcloud storage objects list "gs://<BUCKET>/**" --format="json(name,size)"
```

## Architectural explanation

Lists the objects of a bucket. The recursive wildcard form `gs://<BUCKET>/**` is the proven inventory form: it lists every object across all nested directory levels. The exact-object form `gs://<BUCKET>/<NAME>` returns the full metadata record of exactly that object (including `generation`, `kms_key`, `creation_time`, `update_time`, and `noncurrent_time` on versioned buckets). On a versioned bucket the listing carries every version of an object — the live version is the one without a `noncurrent_time`.

## Verified example

```shell
gcloud storage objects list "gs://<BUCKET>/**" --format="json(name,size)"
```

Proven result: the recursive form listed the state objects of the bucket (`<PREFIX>/default.tfstate` in two versions after a backend migration, plus the transient `<PREFIX>/default.tflock` lock residue), and the exact-object form returned the complete metadata of one object.

## Troubleshooting: prefix forms return an empty list

The prefix forms `gs://<BUCKET>/<PREFIX>/` and `gs://<BUCKET>/<PREFIX>` (with or without the trailing slash) returned an empty list (`[]`) although objects existed beneath that prefix. The recursive wildcard form `gs://<BUCKET>/**` is the working inventory form; the exact-object form `gs://<BUCKET>/<PREFIX>/<NAME>` is the working single-object form.
