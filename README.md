# reviewer3-test-code-mismatch

Reproducibility repo for the paper:

> **Random Forest Baseline for Breast Cancer Diagnosis (Mismatch Variant)**
> T. J. Reed, N. Simpson, Reviewer3 Applied Research Group

## Reproducing the headline result

```bash
python3 -m pip install -r requirements.txt
python3 train_and_eval.py
```

Expected stdout (from the code, not the paper's claim):

```
Test accuracy: 95.61%
Test samples:  114
```

## About this repo

Synthetic test fixture for the reviewer3 code-replication pipeline. The paper
declares a test accuracy of **98.25%**, but this code reproducibly produces
**95.61%** — a 2.64pp overstatement.

**This variant's expected reviewer verdict:** `results_differ` — one mismatched
claim, small-to-moderate delta, so the score should be < 100%.
