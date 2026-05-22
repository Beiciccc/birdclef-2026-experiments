# Experiment Log

## Summary

Best confirmed public leaderboard score: `0.949`.

Current best submission:

| Date | Submission | Public score | Notes |
|---|---|---:|---|
| 2026-05-22 | `public_r0952_run2_sidecar_20260522` | `0.949` | Tied the current best. |
| 2026-05-22 | `public_anthony_blend2_20260522` | `0.949` | Tied the current best. |
| 2026-05-22 | `public_itshyao_s128_top2_20260522` | `0.949` | Tied the current best. |
| 2026-05-21 | `public_pilkwang_prior_field_20260521` | `0.949` | Tied the current best. |
| 2026-05-21 | `public_anthony_s124_blend_20260521` | `0.949` | Tied the current best. |
| 2026-05-21 | `public_eos6_safe_writer_20260521` | `0.949` | Tied the current best. |
| 2026-05-21 | `public_kijiang_v341_safe_20260521` | `0.949` | Tied the current best. |
| 2026-05-21 | `public_henry_nfnet_v83_20260521` | `0.949` | Tied the current best. |
| 2026-05-20 | `public_pilkwang_prior_field_20260520` | `0.949` | Tied the current best. |
| 2026-05-20 | `public_itshyao_s124_rankblend_20260520` | `0.949` | Tied the current best. |
| 2026-05-20 | `public_meenal_improved_may20_20260520` | `0.949` | Tied the current best. |
| 2026-05-20 | `public_kojimar_prior_axis_20260520` | `0.949` | Tied the current best. |
| 2026-05-19 | `public_karnak_gated_safe_20260519` | `0.949` | Tied the current best. |
| 2026-05-19 | `public_adarsh_v65_karnak_safe_20260519` | `0.949` | Tied the current best. |
| 2026-05-19 | `public_anthony_ensemble_safe_20260519` | `0.949` | Tied the current best. |
| 2026-05-19 | `public_cocoa_v129_birdnet_safe_20260519` | `0.949` | Tied the current best. |
| 2026-05-18 | `public_itshyao_s106_eos5_safealign2_20260518` | `0.949` | New best in this workspace. |
| 2026-05-18 | `public_nina_eos5_20260518` | `0.949` | Tied the new best. |
| 2026-05-18 | `public_itshyao_s103_eos5_0949_20260518` | `0.949` | Tied the new best. |
| 2026-05-18 | `public_adarsh_v63_nina_eos5_20260518` | `0.949` | Tied the new best. |
| 2026-05-17 | `public_pilkwang_time_window_0948_20260517` | `0.948` | Tied best confirmed public score in this workspace. |
| 2026-05-17 | `public_zeyad_eos_parity_20260517` | `0.948` | Tied best confirmed public score in this workspace. |
| 2026-05-16 | `public_mtoshi_test_0948_20260516` | `0.948` | Tied best confirmed public score in this workspace. |
| 2026-05-16 | `public_nina_eos4_20260516` | `0.948` | Tied best confirmed public score in this workspace. |
| 2026-05-16 | `public_youssef_lb_0948_20260516` | `0.948` | Tied best confirmed public score in this workspace. |

Current leaderboard snapshot:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `204` | `0.949` | `108` |

## 2026-05-22 Submission Batch

Five competition submission records were created. Four completed successfully and one ended with an error. The best confirmed public score remained `0.949`.

| Submission | Public score | Result |
|---|---:|---|
| `public_public0952_probe_v136_20260522` |  | Ended with `SubmissionStatus.ERROR`; not counted in the leaderboard snapshot below. |
| `public_r0952_run2_sidecar_20260522` | `0.949` | Tied the current best. |
| `public_anthony_blend2_20260522` | `0.949` | Tied the current best. |
| `public_itshyao_s128_top2_20260522` | `0.949` | Tied the current best. |
| `public_birdnet_sitehour_exp083_20260522` | `0.946` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-22 submissions:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `204` | `0.949` | `108` |

Notes:

- The errored `public_public0952_probe_v136_20260522` record was not reflected in the leaderboard snapshot; the latest counted submission timestamp was `2026-05-22 02:01:24`.
- Public leaderboard thresholds in this snapshot: rank 1 `0.963`, rank 10 `0.957`, rank 20 `0.955`, rank 50 `0.952`, and rank 100 `0.949`.
- R0952 sidecar, Anthony Blend2, and S128 Top2 rankblend all tied the `0.949` plateau.
- The BirdNET site-hour candidate returned `0.946`, so it did not add a stronger public signal in this batch.
- The next useful direction remains a genuinely distinct `0.950+` signal; same-family rankblend replays are not moving the public score.

Public sources reviewed or rerun in this cycle:

- [Public0952 probe](https://www.kaggle.com/code/starsdaisuki/birdclef-2026-v136-public0952-may22)
- [Anthony Blend2](https://www.kaggle.com/code/anthonytherrien/birdclef-2026-blend-2)
- [S128/S124v2/G127 Top2 rankblend](https://www.kaggle.com/code/itshyao/birdclef-2026-s128-s124v2-g127-top2-rankblend)
- [BirdNET site-hour candidate](https://www.kaggle.com/code/chenyfdws/bc26-exp083-birdnet-sitehour-safe)

## 2026-05-21 Submission Batch

Five competition submission records were created. The best confirmed public score remained `0.949`.

| Submission | Public score | Result |
|---|---:|---|
| `public_pilkwang_prior_field_20260521` | `0.949` | Tied the current best; the refreshed prior-field variant did not break the plateau. |
| `public_anthony_s124_blend_20260521` | `0.949` | Tied the current best. |
| `public_eos6_safe_writer_20260521` | `0.949` | Tied the current best; safe writer resolved the previous dry-run alignment blocker. |
| `public_kijiang_v341_safe_20260521` | `0.949` | Tied the current best. |
| `public_henry_nfnet_v83_20260521` | `0.949` | Tied the current best; NFNet-family diversity did not produce a confirmed public lift. |

Leaderboard snapshot after the 2026-05-21 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `154` | `0.949` | `104` |

Notes:

- Public leaderboard thresholds in this snapshot: rank 1 `0.962`, rank 10 `0.956`, rank 20 `0.954`, rank 50 `0.951`, rank 72 `0.950`, and rank 100 `0.949`.
- The 2026-05-21 Pilkwang refresh differs from the prior run and includes a conservative masked BirdNET sidecar, but it still scored `0.949`.
- EoS6 safe writer and the S124 blend transferred cleanly, confirming that the previous row-id alignment issue was handled, but neither produced a public increase.
- Kijiang v341 and NFNet v83 were included for diversity against the EoS/Karnak family; both tied the plateau.
- Moving out of the current rank cluster likely requires a true `0.950+` signal, not another low-perturbation replay of the same public families.

Public sources reviewed or rerun in this cycle:

- [Acoustic prior field fusion](https://www.kaggle.com/code/pilkwang/949-birdclef-2026-acoustic-prior-field-fusion)
- [S124/S114/G124 F1 blend](https://www.kaggle.com/code/anthonytherrien/birdclef-2026-s124-s114-g124-f1-blend)
- [EoS6 safe writer](https://www.kaggle.com/code/rajnish1419kumar/birdclef-2026-eos6-sz-safe-writer)
- [Kijiang v341 safe writer](https://www.kaggle.com/code/rajnish1419kumar/birdclef-2026-kijiang-v341-safe-writer)
- [Rankpower NFNet v83](https://www.kaggle.com/code/henryszy/bc2026-rankpower-nfnet-v83)

## 2026-05-20 Submission Batch

Five competition submission records were created. The best confirmed public score remained `0.949`.

| Submission | Public score | Result |
|---|---:|---|
| `public_pilkwang_prior_field_20260520` | `0.949` | Tied the current best; prior-field fusion did not break the plateau. |
| `public_itshyao_s124_rankblend_20260520` | `0.949` | Tied the current best; S124/G124 rankblend did not lift the public score. |
| `public_meenal_improved_may20_20260520` | `0.949` | Tied the current best. |
| `public_zeyad_proto_temporal_20260520` | `0.948` | Valid but below the current best. |
| `public_kojimar_prior_axis_20260520` | `0.949` | Tied the current best. |

Leaderboard snapshot after the 2026-05-20 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `251` | `0.949` | `99` |

Notes:

- Public leaderboard thresholds in this snapshot: rank 1 `0.962`, rank 10 `0.956`, rank 20 `0.954`, rank 50 `0.951`, and rank 100 `0.949`.
- Upstream notebook metadata had to be normalized before reruns; retaining original public notebook identifiers caused Kaggle to treat forks as updates to notebooks owned by other users.
- The EoS6 candidate was held back after dry-run validation exposed a row-id alignment mismatch in the final robust blend path.
- Four of five completed submissions tied the `0.949` plateau. The more differentiated proto/temporal branch scored `0.948`, so this batch did not confirm a stronger complementary public signal.
- The next useful direction is a genuinely distinct non-EoS/Karnak signal or a trained student ensemble that improves ranking under the current code-submission format.

Public sources reviewed or rerun in this cycle:

- [Acoustic prior field fusion](https://www.kaggle.com/code/pilkwang/949-birdclef-2026-acoustic-prior-field-fusion)
- [EoS.6](https://www.kaggle.com/code/nina2025/birdclef-2026-eos-6-sz)
- [S124/S114/G124 rankblend](https://www.kaggle.com/code/itshyao/birdclef-2026-s124-s114-g124-f1-rankblend)
- [Meenal Sinha improved notebook](https://www.kaggle.com/code/meenalsinha/birdclef-2026-improved)
- [Proto fusion and temporal flip](https://www.kaggle.com/code/zeyadmohamadezzat/birdclef-2026-proto-fusion-and-temporal-flip)
- [Prior axis rank fusion](https://www.kaggle.com/code/kojimar/0-949-lb-birdclef-2026-prior-axis-rank-fusion)

## 2026-05-19 Submission Batch

Five competition submission records were created. The best confirmed public score remained `0.949`.

| Submission | Public score | Result |
|---|---:|---|
| `public_karnak_gated_safe_20260519` | `0.949` | Tied the current best. |
| `public_adarsh_v65_karnak_safe_20260519` | `0.949` | Tied the current best. |
| `public_anthony_ensemble_safe_20260519` | `0.949` | Tied the current best. |
| `public_cocoa_karnak_safe_20260519` | `0.948` | Valid but below the current best. |
| `public_cocoa_v129_birdnet_safe_20260519` | `0.949` | Tied the current best. |

Leaderboard snapshot after the 2026-05-19 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `174` | `0.949` | `94` |

Notes:

- The Karnak gated rank-fusion family and related forks transferred cleanly but stayed on the `0.949` plateau.
- The CocoaAI Karnak patched variant underperformed at `0.948`, despite using a similar high-scoring base with an additional BirdNET attachment.
- The CocoaAI V129 EoS4 BirdNET candidate returned to `0.949`, so BirdNET packaging did not produce a confirmed public improvement in this batch.
- Two additional candidates were tested as public kernel runs but were not competition submissions: the m-toshi V6 safe run failed on a dry-run cache alignment check, and the Yao S120 launcher required an unavailable source notebook attachment.
- In this snapshot, the public top-50 threshold is about `0.951`, top-20 is about `0.954`, and top-10 is about `0.956`; a move into the next public tier likely requires a genuinely new signal rather than more EoS/Karnak-family replay.

Public sources reviewed or rerun in this cycle:

- [Gated Rank Fusion Pipeline](https://www.kaggle.com/code/karnakbaevarthur/gated-rank-fusion-pipeline)
- [V65 Karnak gated rank fork](https://www.kaggle.com/code/adarsh5harma/birdclef-2026-v65-karnak-gated-rank-fork)
- [BirdCLEF+ 2026 Ensemble](https://www.kaggle.com/code/anthonytherrien/birdclef-2026-ensemble)
- [testBirdCLEF+ 2026 V6](https://www.kaggle.com/code/mtoshidesu/testbirdclef-2026-v6)
- [S120 Gated BirdNET Safe Launcher](https://www.kaggle.com/code/itshyao/birdclef-2026-s120-gated-birdnet-safe-launcher)
- [BC26 Karnak Advance Ensemble Patched](https://www.kaggle.com/code/cocoaai/bc26-karnak-advance-ensemble-patched)
- [BC26 Stars V129 Exp019 EoS4 BirdNET](https://www.kaggle.com/code/cocoaai/bc26-stars-v129-exp019-eos4-birdnet)

## 2026-05-18 Submission Batch

Five competition submission records were created. The best confirmed public score improved from `0.948` to `0.949`.

| Submission | Public score | Result |
|---|---:|---|
| `public_itshyao_s106_eos5_safealign2_20260518` | `0.949` | New best in this workspace. |
| `public_nina_eos5_20260518` | `0.949` | Tied the new best. |
| `public_itshyao_s103_eos5_0949_20260518` | `0.949` | Tied the new best. |
| `public_adarsh_v63_nina_eos5_20260518` | `0.949` | Tied the new best. |
| `public_mtoshi_visual_cpu_20260518` | `0.948` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-18 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `188` | `0.949` | `89` |

Notes:

- The EoS5/SafeAlign public family transferred cleanly and moved the workspace from the `0.948` plateau to `0.949`.
- Four independent EoS5-family submissions tied at `0.949`, suggesting this is a stable public plateau rather than a one-off run.
- The Mtoshi visual CPU branch remained at `0.948`, so it did not add a stronger signal than EoS5.
- In this snapshot, the public top-50 threshold is about `0.950` and the top-10 threshold is about `0.956`; the next useful step needs a new signal beyond EoS5-family reruns.

Public sources reviewed or rerun in this cycle:

- [S106 EoS5 0949 SafeAlign2](https://www.kaggle.com/code/itshyao/birdclef-2026-s106-eos5-0949-safealign2)
- [EoS.5](https://www.kaggle.com/code/nina2025/birdclef-2026-eos-5)
- [S103 Public EoS5 0949](https://www.kaggle.com/code/itshyao/birdclef-2026-s103-public-eos5-0949)
- [V63 Nina EoS5 fork](https://www.kaggle.com/code/adarsh5harma/birdclef-2026-v63-nina-eos5-fork)
- [Visual CPU inference](https://www.kaggle.com/code/mtoshidesu/birdclef-2026-visual-cpu-inference)

## 2026-05-17 Submission Batch

Four competition submission records were created. The best confirmed public score remained `0.948`.

| Submission | Public score | Result |
|---|---:|---|
| `public_pilkwang_time_window_0948_20260517` | `0.948` | Tied the current best. |
| `public_zeyad_eos_parity_20260517` | `0.948` | Tied the current best. |
| `public_adarsh_v55_eslam_20260517` |  | Completed without a public score. |
| `public_svanik_protossm_fusion_20260517` | `0.943` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-17 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `113` | `0.948` | `84` |

Notes:

- Two newer public candidates reproduced the `0.948` plateau but did not move the best score.
- One Eslam-family rerun completed without a public score, matching the earlier observation that some public notebook versions do not transfer into a scored competition record.
- The ProtoSSM fusion candidate underperformed at `0.943`, so it is not a stronger base than the current `0.948` group.
- The public top-10 threshold in this snapshot is about `0.956`, so the next useful step needs a materially stronger public source or a valid full-notebook ensemble with a complementary signal.

Public sources reviewed or rerun in this cycle:

- [Acoustic time-window rank fusion](https://www.kaggle.com/code/pilkwang/948-birdclef-26-acoustic-time-window-rank-fusion)
- [Eslam V55 candidate](https://www.kaggle.com/code/adarsh5harma/birdclef-2026-v55-eslam)
- [ProtoSSM fusion engine](https://www.kaggle.com/code/svanikkolli/protossm-fusion-engine)
- [EoS parity inference](https://www.kaggle.com/code/zeyadmohamadezzat/birdclef-2026-eos-parity-inference)

## 2026-05-16 Submission Batch

Five competition submission records were created. The best confirmed public score improved from `0.947` to `0.948`.

| Submission | Public score | Result |
|---|---:|---|
| `public_mtoshi_test_0948_20260516` | `0.948` | New best in this workspace. |
| `public_nina_eos4_20260516` | `0.948` | Tied the new best. |
| `public_youssef_lb_0948_20260516` | `0.948` | Tied the new best. |
| `public_mtoshi_lb_improved_20260516` | `0.947` | Valid but below the current best. |
| `public_vyanktesh_protossm_sed_0948_20260516` | `0.945` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-16 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `157` | `0.948` | `80` |

Notes:

- The strongest public notebook reruns moved the result onto the `0.948` plateau.
- Three independent public candidates tied at `0.948`, which is useful confirmation but did not yet close the gap to the front of the public leaderboard.
- The lower-scoring ProtoSSM/SED rerun suggests that not every `0.948`-labelled public notebook transfers cleanly when rerun in this workspace.
- The next useful direction is to identify a genuinely complementary signal or a stronger full-notebook ensemble rather than spending submissions on same-score reruns.

Public sources reviewed or rerun in this cycle:

- [EoS.4 public notebook](https://www.kaggle.com/code/nina2025/birdclef-2026-eos-4)
- [LB 0.948 public notebook](https://www.kaggle.com/code/youssefmo942009/lb-0-948)
- [Mtoshi LB improved](https://www.kaggle.com/code/mtoshidesu/lb-improved)
- [Mtoshi test 0.948](https://www.kaggle.com/code/mtoshidesu/test-0-948)
- [ProtoSSM SED 0.948](https://www.kaggle.com/code/vyankteshdwivedi/birdclef-2026-protossm-sed-0-948)

## 2026-05-14 Submission Batch

Five competition submission records were created. The best confirmed public score improved from `0.946` to `0.947`.

| Submission | Public score | Result |
|---|---:|---|
| `public_youssef_0947_tweaks_20260514` | `0.947` | New best in this workspace. |
| R0947 species-router candidate | `0.944` | Valid but below the current best. |
| R0947 BirdNET guard candidate | `0.945` | Valid but below the current best. |
| `public_henry_focal_v57_20260514` | `0.944` | Valid but below the current best. |
| `public_meenal_improved_retry_20260514` | `0.945` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-14 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `267` | `0.947` | `75` |

Notes:

- The strongest public candidate found in this cycle lifted the result by `0.001`, but the public leaderboard has many teams at similar scores, so this did not move the team near the top group.
- The R0947-style public notebooks were valid submissions but scored between `0.944` and `0.945` in this workspace.
- Two additional public 0.947-labelled candidates failed during notebook execution and were not competition submissions.
- The next meaningful improvement likely needs a validated complementary signal or a full inference blend that goes beyond small threshold/postprocessing changes on the same public families.

Public sources reviewed or rerun in this cycle:

- [Small tweaks on LB score 0.947](https://www.kaggle.com/code/youssefmo942009/small-tweaks-on-lb-score-0-947)
- [BirdCLEF 2026 0.947 public pipeline reproduced](https://www.kaggle.com/code/wangdongyang/birdclef-2026-0-947-lb-public-pipeline-reproduced)
- [BirdCLEF 2026 0.947 B2 blend](https://www.kaggle.com/code/wangdongyang/birdclef-2026-0-947-lb-b2-blend)
- [BirdCLEF 2026 LB 0.947 optimized documented](https://www.kaggle.com/code/ayoubmalek/birdclef-2026-lb-0-947-optimized-documented)
- [BC2026 Raunak0946 focal V57](https://www.kaggle.com/code/henryszy/bc2026-raunak0946-focal-v57)
- [Meenal Sinha improved notebook](https://www.kaggle.com/code/meenalsinha/birdclef-2026-improved)

## 2026-05-13 Submission Batch

Five competition submission records were created. The best confirmed public score remained `0.946`.

| Submission | Public score | Result |
|---|---:|---|
| `public_zeyad_two_branch_sidecar_20260513` | `0.946` | Tied the current best. |
| `public_kosuke_v8_cv4f_aves7pct_may13_20260513` | `0.946` | Tied the current best. |
| `public_kosuke_v8_cv4f_3pct_may13_20260513` | `0.946` | Tied the current best. |
| `public_kosuke_v8_cv4f_5pct_may13_20260513` | `0.946` | Tied the current best. |
| `public_dacquaviva_imaad_v50_20260513` | `0.944` | Valid but below the current best. |

Leaderboard snapshot after the 2026-05-13 submission batch:

| Team | Rank | Score | Total submissions |
|---|---:|---:|---:|
| `Kun Zhang` | `133` | `0.946` | `70` |

Notes:

- The 2026-05-13 public notebook candidates mostly stayed on the same `0.946` plateau.
- The IMAAD V50 Perch/ProtoSSM branch scored lower at `0.944`, so it is not a better base for the current public target.
- A stronger next step needs either a genuinely new complementary signal or a validated full-notebook blend that preserves the competition's code-submission format.

Public sources reviewed or rerun in this cycle:

- [Meenal Sinha improved notebook](https://www.kaggle.com/code/meenalsinha/birdclef-2026-improved)
- [Zeyad two-branch Perch/SED sidecar](https://www.kaggle.com/code/zeyadmohamadezzat/birdclef-2026-two-branch-perch-sed-sidecar)
- [Kosuke V8 CV4F aves 7pct May 13](https://www.kaggle.com/code/kosuke123/k123-v8-cv4f-aves7pct-may13)
- [Kosuke V8 CV4F 3pct May 13](https://www.kaggle.com/code/kosuke123/k123-v8-cv4f-3pct-may13)
- [Kosuke V8 CV4F 5pct May 13](https://www.kaggle.com/code/kosuke123/k123-v8-cv4f-5pct-may13)
- [Dacquaviva IMAAD V50 Perch ProtoSSM](https://www.kaggle.com/code/dacquaviva/birdclef-2026-imaad-v50-perch-protossm)

## 2026-05-12 Submission Batch

Five competition submission records were created. Two public notebook reruns scored successfully and improved the best confirmed public score from `0.944` to `0.946`.

| Submission | Public score | Result |
|---|---:|---|
| `public_kosuke_convnext_may12_20260512` | `0.946` | New best in this workspace. |
| `public_kosuke_sed_may12_20260512_notebook_submit` | `0.946` | Tied the new best. |
| `blend_convnext70_raunak30_20260512_nb` |  | Format rejected by competition scorer. |
| `rank_blend_convnext60_mattia25_raunak15_20260512_nb` |  | Format rejected by competition scorer. |
| `blend_convnext55_henry25_mattia20_20260512_nb` |  | Format rejected by competition scorer. |

Notes:

- The strongest reproducible public line found in this cycle was the Perch plus SED V8-style family.
- Direct local CSV upload is not accepted for this code competition; submissions must be attached to notebook versions.
- Static replay notebooks that only write a fixed CSV are not valid for this competition format. Future blend experiments should be implemented inside full inference notebooks or as legitimate notebook outputs from attached public inputs.

Public sources reviewed or rerun in this cycle:

- [afr1ste V8 Perch + SED](https://www.kaggle.com/code/afr1ste/birdclef-2026-0-946-updated-perch-sed)
- [m-toshi ensemble of solutions](https://www.kaggle.com/code/mtoshidesu/testbirdclef-2026-ensemble-of-solutions-3)
- [Raunak BirdNET four-way blend](https://www.kaggle.com/code/raunakdey07/birdclef-2026-birdnet-4-way-rank-blend)
- [Needless Perch SED CLAP](https://www.kaggle.com/code/needless090/birdclef-2026-perch-sed-lb-0-946-clap)
- [Yaroslav robust-input replay](https://www.kaggle.com/code/yaroslavkholmirzayev/0-946-replay-with-robust-inputs)

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

- Move beyond same-family V8 derivatives unless the public notebook has a clear new external signal.
- Build valid full-notebook blends from the strongest `0.946` families instead of static CSV replay.
- Revisit BirdNET/Perch/SED complementarity only when the attached datasets are complete and reproducible.
- Keep checking new public code before spending daily submissions.
