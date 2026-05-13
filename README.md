# Namespace Architecture and Early-Stage Procedural Inference: Study 1 Data

This repository contains prompt templates, coded datasets, metadata, and normalized raw model responses for Study 1, a controlled structural-probe study examining how frontier AI-mediated retrieval systems operationalize namespace-level structural signals during early-stage source triage under zero-content conditions.

The study investigates *Signal Gap*, defined as the structural absence of sufficiently interpretable subject-area signals at the namespace layer for reliable early-stage procedural differentiation within sequential AI-mediated retrieval systems. All summary tables and analyses reported in the accompanying paper are derived from the datasets provided here.

---

## Repository Contents

* `prompts/` — prompt templates used across experimental conditions.
* `data/raw/` — normalized raw model responses reconstructed to one row per trial where possible.
* `data/processed/` — coded response datasets and derived coding sheets.
* `data/metadata/` — codebooks, validation lists, and allowed-value definitions.
* `manifest.csv` — file-level inventory of repository contents.
* `data_dictionary.md` — field-level documentation for interpreting datasets.

---

## Study Design Overview

The study employed semantically opaque fictitious domain stems paired systematically with both general-purpose namespaces (`.com`, `.org`) and sector-designated namespaces (`.med`, `.finance`, `.legal`, `.kids`) in order to isolate the independent procedural effect of namespace-level structure during early-stage source triage.

Experimental conditions examined how frontier AI systems operationalized namespace-level informational structure under zero-content conditions prior to downstream retrieval and verification. Prompt conditions included:

* full triage evaluation,
* comparative handling assessment,
* constrained interpretation,
* procedural classification,
* verification prioritization,
* and forced-choice routing tasks.

The primary fictitious stems used in the study were:

* `lanteravia`
* `merquonix`
* `caldrison`

Semantically opaque fictitious stems were intentionally used in order to isolate the independent procedural effect of namespace-level structure during early-stage source triage. Although some domain stems may appear semantically suggestive or reflect prior model exposure, they do not provide a sufficiently reliable or scalable mechanism for resolving Signal Gap conditions across general-purpose namespace environments.

At the time of testing, each fictitious stem remained unregistered across all evaluated namespace conditions in order to minimize contamination from existing domain associations or prior retrieval exposure.

Models represented in the dataset include:

* Claude (Sonnet 4.6, Anthropic)
* ChatGPT (GPT-5.3, OpenAI)
* Gemini (3.1 Flash, Google)
* Perplexity (Sonar, Perplexity AI)

Model versions reflect default consumer-interface configurations at the time of testing (April 2026).

---

## Data Preparation

The repository package includes several normalization and preparation steps:

* Conversion of uploaded spreadsheets and CSVs into UTF-8 GitHub-compatible CSV files.
* Separation of multi-tab Excel workbooks into independent CSV datasets.
* Resolution of spreadsheet formulas to stored values where possible.
* Reconstruction of raw response sheets into one row per experimental trial where feasible.
* Export of hidden workbook validation lists into visible metadata files.
* Exclusion of original `.xlsx` workbooks to reduce embedded workbook metadata exposure.

---

## Replication Notes

These datasets support replication of the reported coding procedures and summary analyses. Because frontier AI system behavior varies across model versions, interfaces, safety policies, and retrieval conditions, the files should be interpreted as recorded outputs from the reported testing period rather than as guarantees of future response stability.

The study intentionally isolated namespace-level structural signals under zero-content conditions. The datasets therefore reflect early-stage procedural inference behavior rather than end-to-end retrieval performance.

---

## Data Use

These materials are provided for replication, methodological comparison, secondary analysis, and related research purposes. Users are free to reuse and adapt the data with appropriate citation.

---

## Citation

If you use this dataset, please cite:

Fassett, Ray. (2026). *Namespace Architecture and Early-Stage Procedural Inference — Study 1 Data.*

---

## Contact

For questions, collaborations, or extensions of this work:

Ray Fassett  
rfassett [at] trust.med