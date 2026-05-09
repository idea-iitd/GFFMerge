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
  cache/
```

## Preparation
- The notebooks invoke `../scripts/prepare_m3gnet_data.py` and related utilities to build prepared datasets and configs.
- Update dataset paths in the notebook configuration cells if your raw data is stored elsewhere.

## Notes
- Do not commit raw data, caches, or generated DBs to the repo.
