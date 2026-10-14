# Educators — ERSILIA

**Project:** ERSILIA  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/ersilia-os/ersilia  
**Pinned commit:** `5d3b9ab7d75956590e43a2d689f2df97b42e1839`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e453e96daa669e0f7360025868b389dc642a5643a81682dd67ae2b9b35ec12d7`  
**Date:** October 2026

## Teaching with ERSILIA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e453e96daa669e0f7360025868b389dc642a5643a81682dd67ae2b9b35ec12d7` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
