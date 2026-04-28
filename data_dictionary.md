# Data Dictionary

This repository contains CSV exports and normalized response datasets for Study 1: Top-Level Domain Signals, Signal Gap, and AI Source Triage.

## Core identifiers

|Field|Meaning|
|-|-|
|`study\_id`|Study identifier used in the source files.|
|`trial\_id`|Unique trial identifier where available.|
|`run\_id`|Replication/run identifier.|
|`model\_name` / `model`|AI model used for the response.|
|`timestamp`|Collection timestamp as recorded in the original data.|
|`domain`|Full domain stimulus.|
|`stem`|Semantically opaque domain stem.|
|`tld`|Top-level domain condition.|
|`prompt\_type` / `prompt\_version` / `prompt\_id`|Prompt condition identifiers.|

## Key coded dimensions

|Field|Meaning|
|-|-|
|`classification`|Sector classification output such as `medical`, `unclear`, or `other`.|
|`handling\_path` / `selected\_path`|Assigned triage path.|
|`risk\_weighting`|Low, medium, or high risk coding.|
|`justification\_type` / `explanation\_type`|Reasoning pattern or explanation category.|
|`difference\_flag`|Prompt 2 indicator for whether the model reported a handling difference.|
|`primary\_driver`|Main stated basis for the model decision.|
|`structural\_signal\_acknowledged`|Indicator for whether the model acknowledged the namespace-level signal.|
|`caution\_count`|Count of explicit hedging expressions under the study's coding rule.|
|`raw\_response` / `raw\_response\_text`|Model response text reconstructed to one row per trial.|

## Notes

* CSV files are UTF-8 encoded.
* Original Excel workbook tabs were exported to CSV, and formulas were resolved to stored values where applicable.
* Raw response files were reconstructed from line-oriented source sheets so that each trial appears as one row where possible.
* The `manifest.csv` file lists every file in this package and its purpose.

