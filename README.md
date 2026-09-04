# Analytics Engineer Interview Field Guide

A practical interview preparation guide for the **Analytics Engineer** role, covering the modern ELT stack: SQL, dbt, Snowflake, data modeling, Git, Airflow, Fivetran, and Tableau.

Built as prep material for a Tableau Developer → Analytics Engineer / Data Engineering transition, but useful for anyone interviewing for an Analytics Engineer position.

**🔗 [Open the live interactive guide](https://jaideepgupta.github.io/dbt_interview/)**

## What's inside

- **68 interview questions and answers**, organized by topic, each with a plain-language explanation, a diagram or example where useful, and a ready-to-say "interview version" of the answer.
- A closing framework — **Source → Grain → Transformation → Quality → Consumption** — for reasoning through any Analytics Engineer question on the fly, instead of reciting memorized answers.
- A 30-day study priority list (Tier 1–4) for what to focus on first.

## Topics covered

| Area | Examples |
|---|---|
| Role & stack fundamentals | Analytics Engineer vs. Data Engineer vs. Data Analyst, ELT vs. ETL |
| Tools | Snowflake, dbt, Fivetran, Airflow, Git, Tableau |
| Data modeling | Staging / intermediate / marts, star schema, fact & dimension tables, grain, cardinality, surrogate keys, SCDs |
| dbt specifics | Models, `ref()`, `source()`, macros, Jinja, snapshots, incremental models, tests, CI/CD |
| SQL | Window functions, deduplication, running totals, top-N-per-group |
| Troubleshooting | Debugging a mismatched Tableau number, handling duplicates/NULLs, schema changes |
| Strategy | Data contracts, semantic layers, a 30-day prep priority list, and full interview-ready narrative answers |

## Files

| File | Description |
|---|---|
| `index.html` | Interactive version — searchable, filterable by category, with a review-progress tracker. See the live link above. |
| [`Analytics Engineer Interview Guide.pdf`](Analytics%20Engineer%20Interview%20Guide.pdf) | Print/PDF version of the full guide |
| [`Analytics Engineer — Interview Questions & Answers.md`](Analytics%20Engineer%20%E2%80%94%20Interview%20Questions%20%26%20Answers.md) | Plain Markdown version — readable directly on GitHub, easy to diff/edit |

## Using the interactive guide

- **Search** across all 68 questions
- **Filter by category**
- **Mark questions as reviewed** to track study progress
- **Expand / collapse all** for quick scanning

## How to use this guide

For each question, try answering out loud in your own words *before* reading the given answer. The "interview version" callouts are meant to be internalized as talking points, not memorized verbatim — the goal is to think in terms of source → grain → transformation → quality → consumption, not to recite tool names.

---

*Personal interview prep notes — not affiliated with Snowflake, dbt Labs, Fivetran, Airflow, or Tableau.*
