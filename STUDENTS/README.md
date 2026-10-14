# Students — PSYCHOPY

**Project:** PSYCHOPY  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/psychopy/psychopy  
**Pinned commit:** `0c0b814a02bdef4e381c9a5fe1d5e9d7cb6f85ef`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d51f2a553cdd52a33c2b28702e93bcb033ed7b3d165b55c57b087e7c51790b38`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0c0b814a02bdef4e381c9a5fe1d5e9d7cb6f85ef`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d51f2a553cdd52a33c2b28702e93bcb033ed7b3d165b55c57b087e7c51790b38`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
