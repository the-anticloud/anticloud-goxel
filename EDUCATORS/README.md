# Educators — GOXEL

**Project:** GOXEL  
**Category:** VOXELIZATION  
**Upstream:** see BENCH.json  
**Pinned commit:** `0e0070383c9ede24b7c43e7a7bb8ed5dee3d366e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `569fe85c97bf3ee9f870e150729d735941ca5711fc115a08627327bdb540463d`  
**Date:** October 2026

## Teaching with GOXEL

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `569fe85c97bf3ee9f870e150729d735941ca5711fc115a08627327bdb540463d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
