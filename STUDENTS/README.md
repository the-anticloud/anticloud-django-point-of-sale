# Students — DJANGO_POINT_OF_SALE

**Project:** DJANGO_POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/betofleitass/django_point_of_sale  
**Pinned commit:** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `75557e118add9dd4ce99c0e26065dd691b06fea9ddab1b46f57c8a952f21b935`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `75557e118add9dd4ce99c0e26065dd691b06fea9ddab1b46f57c8a952f21b935`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
