# panmvpa

**Exploring the Benefit of Precision fMRI for Multivariate Analysis**

Multivariate analysis of task fMRI comparing template-, group-, and individual-level
network definitions.

Neurohackademy Week 2.

## Data

[PAN: Precision targeting of Association Networks](https://openneuro.org/datasets/ds006598/versions/1.0.0)
(ds006598, v1.0.0) — 10 subjects, up to 9 sessions each, 11 tasks + rest. Raw BIDS, ~636 GB.
`derivatives/` in the dataset contains AFNI timing files only; preprocessing is not included.

Data is not tracked in this repo. Set `PANMVPA_DATA` to your local dataset root.

## Setup

```bash
uv venv
source .venv/bin/activate
uv pip install -e ".[dev]"
```

## Layout

```
src/panmvpa/    package code
notebooks/      exploratory notebooks
scripts/        entry points / job scripts
tests/          tests
data/           local data (not tracked)
```
