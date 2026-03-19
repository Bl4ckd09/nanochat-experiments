# d24_asp48_track step 820230 model export

This folder contains a split archive of `model_820230.pt`.

Reconstruct:

```bash
cat model_820230.tar.gz.part-* > model_820230.tar.gz
tar -xzf model_820230.tar.gz
```

Integrity:

```bash
sha256sum -c SHA256SUMS.parts.txt
sha256sum -c SHA256SUM.combined.txt
```
