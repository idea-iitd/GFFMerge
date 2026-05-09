# Data

This repo does not include raw datasets. Place raw inputs under `data/raw/` and prepared outputs will be written to `data/prepared/` by the notebooks.

## Expected layout
```
data/
  raw/
    <dataset_1>/
    <dataset_2>/
    <dataset_3>.xyz
  prepared/
```

## Preparation
- The notebooks invoke `../scripts/convert_deepmd_raw_to_xyz.py` (if needed) and `../scripts/prepare_datasets.py` to build the prepared dataset DBs in `data/prepared/`.
- Update the dataset paths in the notebook configuration cells if your raw data is stored elsewhere.

## Notes
- Do not commit raw data or generated DBs to the repo.
