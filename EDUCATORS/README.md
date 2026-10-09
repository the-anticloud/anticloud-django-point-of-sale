# Educators — DJANGO_POINT_OF_SALE

**Project:** DJANGO_POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/betofleitass/django_point_of_sale  
**Pinned commit:** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `75557e118add9dd4ce99c0e26065dd691b06fea9ddab1b46f57c8a952f21b935`  
**Date:** October 2026

## Teaching with DJANGO_POINT_OF_SALE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `75557e118add9dd4ce99c0e26065dd691b06fea9ddab1b46f57c8a952f21b935` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
