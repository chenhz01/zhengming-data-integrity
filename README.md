# zhengming-data-integrity

> **Data Integrity** — family index of the [zhengming-toolbox](https://github.com/chenhz01/zhengming-toolbox) (105 tools across neglected niches). Each tool: pure standard-library Python, CLI-first, 60+ self-test cases, CI-verified, score-first designed.

Data integrity validators: ETL resume semantics, idempotent consumption, pagination integrity, uniqueness prechecks, key guards, query pattern ledgers.

## Tools in this family (7)

| Tool | What it does | Self-tests |
|---|---|---|
| [etl-resume-spec](https://github.com/chenhz01/etl-resume-spec) | A checkpoint declaration schema and a resume-consistency analyzer for batch · zero-anchor flagship | 60+ (CI) |
| [queue-idempotent-consume](https://github.com/chenhz01/queue-idempotent-consume) | At-least-once delivery is the default in every real queue, so consumers must deduplicate. · zero-anchor flagship | 60+ (CI) |
| [pagination-integrity-check](https://github.com/chenhz01/pagination-integrity-check) | pagination-integrity-check reconciles collected pagination responses before you trust the dataset: it detects missing · zero-anchor flagship | 60+ (CI) |
| [uniqueness-precheck](https://github.com/chenhz01/uniqueness-precheck) | uniqueness-precheck scans a CSV or JSONL batch against your declared unique key *before* the database import, so one d · zero-anchor flagship | 60+ (CI) |
| [primary-key-guard](https://github.com/chenhz01/primary-key-guard) | Catch primary-key drift before bad IDs reach your database. | 60+ (CI) |
| [slow-query-pattern-ledger](https://github.com/chenhz01/slow-query-pattern-ledger) | A stdlib-only ledger for slow-query logs: normalizes SQL into fingerprints (literals -> `?`), aggregates frequency x d · zero-anchor flagship | 60+ (CI) |
| [baseline-drift-ledger](https://github.com/chenhz01/baseline-drift-ledger) | baseline-drift-ledger is an append-only, hash-chained JSONL ledger for benchmark baselines: every entry carries an env · zero-anchor flagship | 60+ (CI) |

## How to choose

Start from the tool that matches your pain; every README has a 60-word first page, a timed Quickstart, and a *When NOT to use* section. All tools are independent — install nothing, clone and run `python self_test.py`.

## Sibling families

[zhengming-agent-governance](https://github.com/chenhz01/zhengming-agent-governance) · [zhengming-code-engineering](https://github.com/chenhz01/zhengming-code-engineering) · [zhengming-security-compliance](https://github.com/chenhz01/zhengming-security-compliance) · [zhengming-ops-performance](https://github.com/chenhz01/zhengming-ops-performance) · [zhengming-content-docs](https://github.com/chenhz01/zhengming-content-docs)

## License & contact

All tools MIT — © zhengming contributors. These are developer tools, not professional advice. Contact: hcac4735@agent.qq.com
