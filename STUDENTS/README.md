# Students — ERSILIA

**Project:** ERSILIA  
**Category:** MEDICINE_DEVELOPMENT  
**Upstream:** https://github.com/ersilia-os/ersilia  
**Pinned commit:** `5d3b9ab7d75956590e43a2d689f2df97b42e1839`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e453e96daa669e0f7360025868b389dc642a5643a81682dd67ae2b9b35ec12d7`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5d3b9ab7d75956590e43a2d689f2df97b42e1839`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `e453e96daa669e0f7360025868b389dc642a5643a81682dd67ae2b9b35ec12d7`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
