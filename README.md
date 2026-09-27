# Herui Dou

**Business analytics · Finance & operations · Reliable AI workflows**  
Singapore · MSc Business Analytics, Nanyang Technological University  
[LinkedIn](https://www.linkedin.com/in/heruidou)

I am exploring full-time opportunities in business/data analysis, finance and payments operations, and AI-enabled operations. My portfolio focuses on turning business rules into working tools, checking the data behind a decision, and making failures visible and explainable.

## Choose a project for your role

Each overview below starts with the business problem, a short demonstration, screenshots and the limits of the evidence. The repositories contain the implementation, tests and operating notes.

| Area | Project and business question | What to look for |
| --- | --- | --- |
| Payments / Finance Operations | [Payment Reconciliation](https://github.com/herui03/payment-reconciliation-workbench/blob/main/docs/HR_OVERVIEW.md) — Do the internal ledger, payment processor and bank agree? | Gross/net matching, ambiguous transactions sent for review, exception history and reproducible daily reports. Python · SQLite · Flask |
| Revenue / Sales Operations | [Revenue & Commission](https://github.com/herui03/revenue-commission-workbench/blob/main/docs/HR_OVERVIEW.md) — What commission is owed, and why did it change? | Cash receipts, split credit, refund clawbacks, frozen period close and variance investigation. Python · SQLite · Flask |
| Business Analysis / Change | [Merchant Onboarding Policy Lab](https://github.com/herui03/merchant-onboarding-change-lab/blob/main/docs/HR_OVERVIEW.md) — How does a policy change become testable software behavior? | Versioned requirements, evidence requests, approval controls and requirement-to-test traceability. Python · SQLite · Flask |
| Data / Commercial Analytics | [Ecommerce Decision Analytics](https://github.com/herui03/ecommerce-decision-analytics/blob/main/docs/HR_OVERVIEW.md) — Which metrics and experiments support a decision? | Offline dashboard, metric-grain checks, time-aware lead scoring and experiment assumptions. SQL · dbt · DuckDB · Python · JavaScript |
| AI Applications / Operations | [Ad Ops Workflow Reliability](https://github.com/herui03/ad-ops-multi-agent/blob/main/docs/HR_OVERVIEW.md) — Can an AI-assisted workflow wait for approval and recover safely? | Persisted approval gates, proposal revisions, replay protection, failure recovery and candid retrieval evaluation. LangGraph · FastAPI · SQLite · React |

**These are independent portfolio prototypes.** The operations workflows use synthetic data and simulated actions. The ecommerce case distinguishes historical public-data artifacts from a reproducible synthetic pipeline. They are not employer systems, client engagements or claims of production impact.

## How to review the work

1. Open a project overview for a 60-second introduction.
2. Follow the demonstration and inspect one normal path and one failure path.
3. Use the README for setup; inspect `docs/`, tests and GitHub Actions for the supporting evidence.

Recorded walkthroughs show saved runs; running an application locally allows inputs to be changed. Automated developer tests are labelled separately from external stakeholder UAT. No real payments or advertising spend are executed.

## Additional work

- [Credit portfolio risk](https://github.com/herui03/credit-portfolio-risk): exposure, concentration, early-warning and stress analysis.
- [AML transaction monitoring](https://github.com/herui03/aml-transaction-monitoring): rules and scored alerts on a synthetic benchmark.
- [AML monitoring console](https://github.com/herui03/aml-monitoring-console): an interactive synthetic-data review interface. [Browser demo](https://herui03.github.io/aml-monitoring-console/)
- [SME survey panel](https://github.com/herui03/sme-risk-survey-panel): survey harmonisation and modelling in R.
- [PDF to audiobook](https://github.com/herui03/pdf2audiobook): a Python text-to-speech utility.

These repositories contain their own methods and limitations; the five featured projects above have the most recent delivery and review notes.

## Development approach

I use AI coding tools openly. For the recent portfolio work, I directed the scope and intended use; Claude Code implemented code, tests and documentation, and Codex independently reviewed selected logic and evidence and requested fixes. The repositories include reproducible demonstrations and learning exercises for practising explanations of the business rules, design choices and limitations.

For a role-specific conversation or a project walkthrough, reach me on [LinkedIn](https://www.linkedin.com/in/heruidou).
