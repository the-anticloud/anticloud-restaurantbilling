# Independent Insurance — RESTAURANTBILLING

**Project:** RESTAURANTBILLING  
**Category:** POS_SYSTEMS  
**Upstream:** see BENCH.json  
**Pinned commit:** `b9c2e02a1442ca71c127b0d0d22579c81466733a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | RESTAURANTBILLING with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `199a454a181775856d78a8cec862bdeeaf89e58d1ce81587ec6cd7a0136abf71`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
