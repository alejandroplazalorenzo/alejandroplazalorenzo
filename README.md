# Alejandro Plaza Lorenzo

Final-year student of **Computer Engineering + Business Administration** (University of Alicante, graduating June 2027).
I build data platforms and LLM pipelines, and I measure how reliable they are.

Since July 2026 I have been building the data platform of a business club for automotive dealer groups in Spain:
ETL of financial statements into PostgreSQL, large-scale review collection, local-LLM classification with validated
output, and a monitor of the Spanish companies gazette. The repositories below rebuild that work on **public data**;
they contain no proprietary code or data.

## Projects

| Project | What it does | Measured result |
|---|---|---|
| [**borme-radar**](https://github.com/alejandroplazalorenzo/borme-radar) | Monitors Spain's companies gazette (BORME) and raises alerts for a watchlist: new companies, director changes, mergers, capital changes, insolvency | 10 days of gazettes parsed into 17,958 announcements and 33,502 typed acts; re-runs never duplicate data |
| [**review-llm-eval**](https://github.com/alejandroplazalorenzo/review-llm-eval) | Classifies Spanish customer reviews with local LLMs under a JSON Schema contract and measures how far the output can be trusted | 350/350 schema-valid outputs on two models; only 56–60 % of reruns produce identical JSON, even at temperature 0 |
| [**spanish-financials-etl**](https://github.com/alejandroplazalorenzo/spanish-financials-etl) | Turns the ESEF annual reports of Spanish listed companies into a validated PostgreSQL dataset, with natural-language-to-SQL on top | 230 filings from 125 companies loaded; NL-to-SQL answers 10 of 12 held-out questions correctly |

## Stack

Python · SQL / PostgreSQL · pandas · pytest · LLMs (Ollama, structured outputs) · Docker · Git · GitHub Actions

## How I work

I build with AI coding assistants and treat their output like any other untrusted input: explicit schemas, tests,
validation reports and measured error rates before anything is called done.

## Contact

[LinkedIn](https://www.linkedin.com/in/alejandroplazalorenzo/) · alejandroplaza.dev@gmail.com
