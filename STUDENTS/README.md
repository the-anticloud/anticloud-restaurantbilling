# Students — RESTAURANTBILLING

**Project:** RESTAURANTBILLING  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `b9c2e02a1442ca71c127b0d0d22579c81466733a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `b9c2e02a1442ca71c127b0d0d22579c81466733a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
