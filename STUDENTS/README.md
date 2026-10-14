# Students — GOXEL

**Project:** GOXEL  
**Category:** VOXELIZATION  
**Upstream:** see BENCH.json  
**Pinned commit:** `0e0070383c9ede24b7c43e7a7bb8ed5dee3d366e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `569fe85c97bf3ee9f870e150729d735941ca5711fc115a08627327bdb540463d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0e0070383c9ede24b7c43e7a7bb8ed5dee3d366e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `569fe85c97bf3ee9f870e150729d735941ca5711fc115a08627327bdb540463d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
