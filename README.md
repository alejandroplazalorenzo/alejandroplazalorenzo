# Alejandro Plaza Lorenzo

Final-year student of **Computer Engineering + Business Administration** (University of Alicante, graduating June 2027).
I build data pipelines and LLM systems, and I measure how far they can be trusted.

Since July 2026 I have built the data platform of a business club for automotive dealer groups in Spain. Each repository
below rebuilds one of those systems on **public data**: the same models, design decisions and most settings, re-measured here.
They contain no proprietary code or data.

**Looking for:** 2027 graduate roles in data engineering, applied AI or software engineering. Open to relocation in Europe.

## Projects

| Project | What it does | Measured result |
|---|---|---|
| [**borme-radar**](https://github.com/alejandroplazalorenzo/borme-radar) | Keeps the record of watched companies in sync with Spain's companies gazette (BORME), keyed by registry sheet, with officer history, dated records and the year each company joined its group, and flags new companies of the watched groups | 18 years of gazettes (146,610 documents, 13.0 million announcements) reprocessed offline; the 22,729 announcements of the watched companies all found within two passes, 98.8% of them linked by registry sheet; parser constants counted on the corpus |
| [**company-news-radar**](https://github.com/alejandroplazalorenzo/company-news-radar) | Watches the press, company newsrooms and official sources (BORME, public grants, EU tenders) for 32 Spanish listed companies: deterministic filters first, then an LLM classifies the rest under a hard daily quota, and repeats of one event are merged | One year of news: 2,809 stories classified, 1,197 visible after merging, 124 on the front page; one-to-one, official records came before a third of the inscribed acts (median 13.5 days ahead) |
| [**review-llm-eval**](https://github.com/alejandroplazalorenzo/review-llm-eval) | Enriches Spanish reviews with a local LLM under a JSON Schema contract, and re-measures each decision of the production pipeline (E1–E10) | qwen3:4b over qwen3:8b: 22.3 vs 13.7 reviews/min, 200/200 schema-valid, better or equal on 7 of 10 checks |
| [**spanish-financials-etl**](https://github.com/alejandroplazalorenzo/spanish-financials-etl) | Loads the ESEF annual reports of Spanish listed companies into a validated PostgreSQL model, with an assistant that answers from fixed, parameterised queries | 230 filings of 125 companies; 27/27 post-load checks; 9/9 figures matched against the published reports |

## Stack

Python · SQL / PostgreSQL · pandas · pytest · LLMs · Docker · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/alejandroplazalorenzo/) · alejandroplaza.dev@gmail.com
