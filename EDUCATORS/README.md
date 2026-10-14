# Educators — RESTAURANTBILLING

**Project:** RESTAURANTBILLING  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `b9c2e02a1442ca71c127b0d0d22579c81466733a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71`  
**Date:** October 2026

## Teaching with RESTAURANTBILLING

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
