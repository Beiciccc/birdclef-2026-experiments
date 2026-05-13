# Data Notes

This repository keeps only lightweight public metadata and result snapshots.

## Included

- `data/submissions/submission_history.csv`: Kaggle submission list snapshot.
- `data/leaderboard/public_leaderboard_2026-05-08.zip`: downloaded public leaderboard snapshot.
- `data/leaderboard/public_leaderboard_2026-05-12.zip`: downloaded public leaderboard snapshot.
- `data/leaderboard/public_leaderboard_2026-05-13.zip`: downloaded public leaderboard snapshot.

## Not Included

- Official BirdCLEF+ 2026 audio and CSV data.
- Training and inference source code.
- Kernel and notebook execution files.
- Feature caches and mel/embedding arrays.
- Model checkpoints and uploaded Kaggle Dataset bundles.
- Temporary kernel output folders.
- Credential or machine-specific configuration.

## Recreating the Data Root

Download from Kaggle:

```bash
kaggle competitions download -c birdclef-2026
```

Extract into a local directory and point scripts to that location using the script-specific data root arguments or configuration.

Expected core files:

```text
taxonomy.csv
sample_submission.csv
train_audio/
train_soundscapes/
train_soundscapes_labels.csv
```

Public auxiliary Kaggle Datasets and kernels are attached through `kernel-metadata.json` files in each selected `kernels/` subdirectory.
