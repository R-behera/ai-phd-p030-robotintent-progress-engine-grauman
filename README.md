# EgoTrace Multimodal Bench: Computer vision for Grauman-Aligned Research

A professor-outreach research proposal aligned with **Kristen Grauman** at **University of Texas at Austin**.

## For Professor Outreach

This repo is intended to support an honest outreach email. It contains a concrete proposal for what value you can add, but it does **not** yet contain completed experiments or results.

Start here:

- `outreach/value_add_packet.md` - professor-specific contribution plan.
- `outreach/email_draft.md` - short mail draft you can personalize before sending.
- `docs/one_page_project_plan.md` - one-page project summary.
- `PROJECT_STATUS.md` - clear statement of what exists and what does not exist yet.

## Research Question

How can a focused, reproducible artifact around **Computer vision** create useful research infrastructure for a lab working on **Computer vision, video understanding, egocentric/embodied perception**?

## Advisor Fit

- **Professor:** Kristen Grauman
- **University:** University of Texas at Austin
- **Program:** Computer Science
- **CSV research area:** Computer vision, video understanding, egocentric/embodied perception
- **Representative paper:** Ego4D: Around the World in 3,000 Hours of Egocentric Video; 2022; CVPR
- **Scholar link:** https://scholar.google.com/scholar?q=Ego4D%3A+Around+the+World+in+3%2C000+Hours+of+Egocentric+Video

## Proposed Research-Grade Deliverable

Build **a robustness and failure-analysis benchmark for vision or vision-language models** with:

- A documented evaluation split with examples and source provenance.
- Baseline results for zero-shot, fine-tuned, and adapted models.
- Failure gallery with tags for viewpoint, object, context, annotation, and shortcut failures.
- A concise report identifying the highest-value next method to try.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `outreach/value_add_packet.md` - value-add plan for this professor.
- `outreach/email_draft.md` - email draft; personalize before sending.
- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/one_page_project_plan.md` - one-page project summary.
- `docs/experiment_plan.md` - baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Proposal scaffold only. Before external use, verify the professor's current lab page and make a selected repo public or shareable.
