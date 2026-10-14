# Ethics — ERSILIA

**Project:** ERSILIA  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/ersilia-os/ersilia  
**Pinned commit:** `5d3b9ab7d75956590e43a2d689f2df97b42e1839`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e453e96daa669e0f7360025868b389dc642a5643a81682dd67ae2b9b35ec12d7`  
**Date:** October 2026

## Position

ERSILIA is packaged for offline deployment with a verifiable audit trail. The
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
