# RePal Packs (`packs-v1`)

Encrypted level-based `RPK1` asset packs for [HclX/RePal](https://github.com/HclX/RePal) (`repal-packs/1`).

- Every `.rpk` payload and TOC is AES-256-GCM encrypted under a per-pack random key wrapped in `pack-manifest.json`.
- Requires a valid 256-bit master key (`REPAL_PACK_KEY` or `<user_dir>/pack.key`) to mount and decrypt.
