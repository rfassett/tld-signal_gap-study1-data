# Top-Level Domain Signals, Signal Gap, and AI Source Triage — Study 1 Data

This repository package contains prompt templates, coded data, and raw model responses for Study 1, a controlled structural-probe study of how large language models use top-level domain (TLD) signals during early-stage source triage under zero-content conditions. All summary tables reported in the paper are derived from the coded datasets provided here.

## Contents

* `prompts/` — prompt templates used in the study.
* `data/raw/` — normalized raw model responses, reconstructed to one row per trial where possible.
* `data/processed/` — coded response data and derived coding sheets.
* `data/metadata/` — codebooks and allowed-value lists.
* `manifest.csv` — file-level inventory.
* `data\_dictionary.md` — field-level notes for interpreting the datasets.

## Study context

The study used semantically opaque domain stems paired with `.med`, `.org`, and `.com` TLDs to isolate namespace-level effects. Models were evaluated under multiple prompt conditions covering full triage, comparative handling, constrained interpretation, and forced-choice path assignment.

Models represented in the data include: Claude (Sonnet 4.6, Anthropic), ChatGPT (GPT-5.3, OpenAI), Gemini (3.1 Flash, Google), and Perplexity (Sonar, Perplexity AI). Model versions reflect default consumer-interface configurations at the time of testing (April 2026).

## Data preparation performed for this package

* Converted uploaded spreadsheets and CSVs into GitHub-friendly UTF-8 CSV files.
* Split multi-tab Excel workbooks into separate CSV files.
* Resolved spreadsheet formulas to stored values where possible.
* Reconstructed raw responses from line-oriented source sheets into one row per trial where possible.
* Exported hidden workbook validation lists into a visible metadata CSV.
* Did not include original `.xlsx` workbooks, reducing the risk of embedded workbook metadata.

## Replication notes

The data support replication of the reported coding and summary analyses. Because model outputs can vary by model version, interface, and run conditions, these files should be treated as the recorded outputs for the reported run rather than a guarantee of future response stability.

## Data Use

These files represent the recorded outputs of specific model versions under controlled conditions at the time of testing. They are made available for replication, secondary analysis, and methodological comparison. Because large language model behavior varies across versions and interfaces, these data should be treated as a historical snapshot rather than a guarantee of future model responses. Users are free to reuse and adapt the data with appropriate citation.

## Citation

If you use this dataset, please cite:

Fassett, Ray. (2026). *Top‑Level Domain Signals, Signal Gap, and AI Source Triage — Study 1 Data*.

## Contact

For questions, collaborations, or extensions of this work, contact the study author rfassett [at] trust.med


