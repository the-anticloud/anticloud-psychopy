# Ethics — PSYCHOPY

**Project:** PSYCHOPY  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/psychopy/psychopy  
**Pinned commit:** `0c0b814a02bdef4e381c9a5fe1d5e9d7cb6f85ef`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d51f2a553cdd52a33c2b28702e93bcb033ed7b3d165b55c57b087e7c51790b38`  
**Date:** October 2026

## Position

PSYCHOPY is packaged for offline deployment with a verifiable audit trail. The
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
