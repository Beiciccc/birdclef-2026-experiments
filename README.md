# BirdCLEF+ 2026 Experiments

Public experiment workspace for the Kaggle [BirdCLEF+ 2026](https://www.kaggle.com/competitions/birdclef-2026) code competition.

This repository contains the public project summary, experiment notes, submission history, and public leaderboard snapshots. It does not include Kaggle competition audio, private configuration, local paths, model checkpoints, or temporary run artifacts.

## Final Result

Competition completed on 2026-06-03.

- Team: `Kun Zhang`
- Final private leaderboard score: `0.941`
- Final private leaderboard rank: `837`
- Final leaderboard submission timestamp: `2026-06-03 11:46:37`
- Final public leaderboard score: `0.950`
- Final public leaderboard rank: `325`
- Submission count: `169`
- Best displayed privateScore in submission history: `0.942` from `public_mtoshi_yaroslav_v221_tax_20260527`

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
