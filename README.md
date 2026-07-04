# Health Insurance Claims Process Improvement — Independent BA Case Study

**Author:** Isabah Tabenda Hasan | **Domain:** Health & Life Insurance — Claims Operations | June 2026

## Why I built this

I wanted hands-on practice with core business analyst methodology — requirements gathering, process mapping, and translating data into recommendations which can be applied to the insurance domain.

## What's inside

- **`BRD_Claims_Process_Improvement.docx`** — full Business Requirements Document: problem statement, stakeholder analysis, business & functional requirements (user stories with acceptance criteria), current- and future-state process maps, KPIs, and next steps.
- **`chart_status.png`, `chart_channel.png`, `chart_type.png`** — supporting data visualizations.
- **`process_current.png`, `process_future.png`** — as-is and to-be process maps.
- **`claims.csv`** — the public sample dataset used (4,500 synthetic health insurance claims).

## Key finding

Across the 4,500 claims analyzed, only **33.8%** were approved on first pass — the rest were denied or left pending with no SLA tracking. That single stat became the anchor for the whole requirements set: standardize intake, validate documentation up front, prioritize the review queue, and give staff and members visibility into resolution time.

## Method

1. Pulled a public sample claims dataset and ran exploratory analysis in Python (pandas) to quantify the problem.
2. Mapped the current-state process based on what the data implied about channels, review steps, and outcomes.
3. Ran a stakeholder analysis (members, adjusters, ops manager, IT, compliance).
4. Wrote business requirements and functional user stories with acceptance criteria.
5. Designed a future-state process and defined KPIs to measure success.

## Note on the data

This uses a public, synthetic sample dataset for practice purposes — it's not real claims data from any insurer. The BRD calls this out explicitly and treats the findings as illustrative, with "validate with real stakeholders" as an explicit next step. That's intentional: it shows I know the difference between a training exercise and a production analysis.
