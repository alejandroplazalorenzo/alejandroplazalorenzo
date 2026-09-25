# Alejandro Plaza Lorenzo

Final-year student of **Computer Engineering + Business Administration** (University of Alicante, graduating June 2027).
I build data pipelines and LLM systems, and I measure how far they can be trusted.

Since July 2026 I have built the data platform of a business club for automotive dealer groups in Spain. Each repository
below rebuilds one of those systems on **public data**: the same models, settings and design decisions, re-measured here.
They contain no proprietary code or data.

**Looking for:** 2027 graduate roles in data engineering, applied AI or software engineering. Open to relocation in Europe.

## Projects

| Project | What it does | Measured result |
|---|---|---|
| [**borme-radar**](https://github.com/alejandroplazalorenzo/borme-radar) | Keeps a watchlist of companies in sync with Spain's companies gazette (BORME), keyed by registry sheet, with officer history and dated records, and flags new companies of the watched groups | 12 months of gazettes (8,026 documents): 1,293 of 1,326 announcements of the watched companies matched by registry sheet |
| [**review-llm-eval**](https://github.com/alejandroplazalorenzo/review-llm-eval) | Enriches Spanish reviews with a local LLM under a JSON Schema contract, and re-measures each decision of the production pipeline (E1–E10) | qwen3:4b over qwen3:8b: 22.3 vs 13.7 reviews/min, 200/200 schema-valid, better or equal on 7 of 10 checks |
| [**spanish-financials-etl**](https://github.com/alejandroplazalorenzo/spanish-financials-etl) | Loads the ESEF annual reports of Spanish listed companies into a validated PostgreSQL model, with an assistant that answers from fixed, parameterised queries | 230 filings of 125 companies; 27/27 post-load checks; 9/9 figures matched against the published reports |

## Stack

Python · SQL / PostgreSQL · pandas · pytest · LLMs · Docker · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/alejandroplazalorenzo/) · alejandroplaza.dev@gmail.com
