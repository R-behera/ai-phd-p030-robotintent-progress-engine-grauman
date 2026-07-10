# Unique Prototype Algorithm

## Algorithm

**GraumanCounterfactualComputerVisionCalibrateMatrix** (`P030-Grauman-ComputerVision`)

## Professor Alignment

- Professor: Kristen Grauman
- Research area: Computer vision, video understanding, egocentric/embodied perception
- Focus terms: Computer vision, video understanding, egocentric, embodied perception

## Core Mechanism

This prototype prioritizes distribution-shift failures with confidence-aware calibration penalties.

## Decision Rule

Rank seed cases by vision-specific priority score with Grauman-aligned focus term 'Computer vision'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `vision` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Kristen Grauman's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
