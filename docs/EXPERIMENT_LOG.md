# Experiment Log

## Summary

Best confirmed public leaderboard score: `0.944`.

Current best submission:

| Date | Submission | Public score | Notes |
|---|---|---:|---|
| 2026-05-08 | `public_raunak_v8_20260508` | `0.944` | Best confirmed public score in this workspace. |

Leaderboard snapshot after the 2026-05-08 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `179` | `0.944` | `60` |

## 2026-05-08 Submission Batch

Five valid competition submissions were completed.

| Submission | Public score | Result |
|---|---:|---|
| `public_henry_mattia_safe_rescue_v16_20260508` | `0.941` | Valid public notebook rerun. |
| `public_raunak_v8_20260508` | `0.944` | New best in this workspace. |
| `public_kamongi_pantanal_distill_20260508` | `0.941` | Valid public notebook rerun. |
| `public_henry_mattia_better_v10` | `0.941` | Valid public notebook rerun. |
| `public_henry_hgnet_v20_20260508` | `0.940` | Valid public notebook rerun with HGNet branch. |

Additional candidates investigated but not used as valid submissions:

| Candidate | Status | Reason |
|---|---|---|
| `wuwenmin_v25b_w10` | Kernel error | Missing public `v02 SED ONNX` file expected by the notebook. |
| `konbu_head_w50_s35_h15` | Preparation error | Constant replacement helper misclassified unchanged target values as missing. |
| `konbu_head_w55_s35_h10` | Preparation error | Same constant replacement issue. |
| `konbu_head_w45_s35_h20` | Preparation error | Same constant replacement issue. |
| `croftadams_v19_quantized` | Kernel error | ONNX Runtime unavailable, TensorFlow fallback failed during SavedModel deserialization. |

## Public Sources Used In The 2026-05-08 Batch

- [Raunak V8](https://www.kaggle.com/code/raunakdey07/birdclef-2026-v8)
- [Henry Safe Rescue V16](https://www.kaggle.com/code/henryszy/bc2026-mattia-safe-rescue-v16)
- [Kamongi Pantanal Distill](https://www.kaggle.com/code/kamongi/pantanal-distill-birdclef2026)
- [Henry HGNet V20](https://www.kaggle.com/code/henryszy/bc2026-mattia-v10-hgnet-v20)

## Earlier Direction Notes

### 2026-04-30: Tucker SED Rank Blend

- Submission: `public_yuriy_dual_tucker_sed_rankblend_w244`
- Public score: `0.938`
- Current best at that time: `public_yuriy_dual_tucker_sed_rankblend_w245 = 0.941`
- Observation: nearby Tucker SED rank-blend weights were not monotonic.

Local score curve observed around this family:

| Variant | Public score |
|---|---:|
| `w24` | `0.934` |
| `w244` | `0.938` |
| `w245` | `0.941` |
| `w247` | `0.938` |
| `w25` | `0.940` |
| `w26` | `0.938` |

Decision: avoid spending further daily submissions on small one-dimensional global blend probes unless paired with a materially different signal.

## Next Directions

- Fix the public Konbu-head preparation helper so unchanged constants count as successfully matched.
- Add an ONNX Runtime wheel/kernel source for Croftadams-style notebooks before retrying that branch.
- Prefer public, fully attachable Kaggle inputs for future submission candidates.
- Focus on complementary signals rather than small global blend-weight probes.
