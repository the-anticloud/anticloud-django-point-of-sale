# Ethics — DJANGO_POINT_OF_SALE

**Project:** DJANGO_POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/betofleitass/django_point_of_sale  
**Pinned commit:** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `75557e118add9dd4ce99c0e26065dd691b06fea9ddab1b46f57c8a952f21b935`  
**Date:** October 2026

## Position

DJANGO_POINT_OF_SALE is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
