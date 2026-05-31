# BirdCLEF+ 2026 Experiments

Public experiment workspace for the Kaggle [BirdCLEF+ 2026](https://www.kaggle.com/competitions/birdclef-2026) code competition.

This repository contains the public project summary, experiment notes, submission history, and public leaderboard snapshots. It does not include Kaggle competition audio, private configuration, local paths, model checkpoints, or temporary run artifacts.

## Current Public Leaderboard

As of 2026-05-31:

- Team: `Kun Zhang`
- Best public score: `0.950`
- Public rank: `208`
- Submission count: `154`
- Best recent submissions: `public_pilkwang_eos_oof_gated_pcen_r3_20260531`, `public_thomas_smart_hybrid_default_20260530`, `public_thomas_smart_hybrid_10s_20260530`, `public_thomas_smart_hybrid_softside_20260530`

## Repository Layout

```text
docs/                    Experiment log and data notes
data/submissions/        Submission history snapshot
data/leaderboard/        Public leaderboard snapshot
```

## Data

Download the official competition data through Kaggle:

```bash
kaggle competitions download -c birdclef-2026
```

The training code expects the extracted competition files under a local data root containing files such as:

```text
taxonomy.csv
sample_submission.csv
train_audio/
train_soundscapes/
train_soundscapes_labels.csv
```

Large derived artifacts are intentionally excluded from Git:

- competition audio
- feature caches
- model checkpoints
- Kaggle Dataset upload bundles
- raw temporary kernel outputs

See [docs/DATA.md](docs/DATA.md) for details.

## Experiment Log

The main result log is in [docs/EXPERIMENT_LOG.md](docs/EXPERIMENT_LOG.md).

## Public Notebook Attribution

Several experiments are forks or controlled reruns of public Kaggle notebooks. The relevant source links are documented in the experiment log and preserved in the notebook/kernel metadata where available.
