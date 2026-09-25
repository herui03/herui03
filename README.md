# Hi, I'm Herui Dou

MSc Business Analytics student at Nanyang Technological University (Nanyang Business School), with a Bachelor of Business in Banking and Finance from NTU. I'm looking for a full-time data analyst, data scientist, business analyst, BI or AI transformation role in Singapore, and I can start immediately.

What I do well is the middle of the pipeline: take a business question from a risk, finance or operations team, get the data right (grain, joins, codeframes, censoring, the things that quietly break an analysis), build the model or dashboard, and explain the result to someone who has to make a decision with it. I work in SQL, Python and R, and I use AI coding tools heavily to build prototypes, agent workflows and internal tools quickly.

Before the MSc I did three data-focused internships in banking and fintech: treasury reconciliation and process automation at Tencent (Python and SQL matching rules across 8 overseas accounts and 30k+ monthly transactions; manual-review rate cut from about 20% to under 2%), retail-banking pricing analytics and UAT at Bank of China Singapore, and counterparty risk and KYC data work in BOC's FI reporting team.

## Projects

Start with **credit-portfolio-risk** for finance and analytical controls, **sme-risk-survey-panel** for data cleaning and modelling, or **ad-ops-multi-agent** for an AI workflow prototype. The tables below link to the code, methods and demos.

### Risk and financial crime analytics

| Project | What it is | Stack |
|---|---|---|
| [aml-transaction-monitoring](https://github.com/herui03/aml-transaction-monitoring) | Rule-based AML monitoring on a 9.5M synthetic-transaction benchmark, evaluated at a fixed analyst review budget, then compared with a gradient-boosted model. The best rule catches 0.07% of laundering at the budget; the model catches 87%. SHAP reasons per alert, a leakage check, a calibration check, and five documented mistakes. [Tableau Public dashboard](https://public.tableau.com/app/profile/herui.dou/viz/AMLTransactionMonitoringRulesvsaScoredModelatAnalystCapacity/Dashboard1) | SQL, DuckDB, Python, scikit-learn, SHAP, Tableau |
| [credit-portfolio-risk](https://github.com/herui03/credit-portfolio-risk) | Limits, concentration, early warning indicators and stress testing on 2.26M US consumer loans. The headline finding is a right-censoring bug: naive vintage default rates showed credit quality improving 90% while the book was actually deteriorating 57%. Every figure is re-derived by a mutation-tested verification script | SQL, Python, Excel, Tableau |
| [aml-monitoring-console](https://github.com/herui03/aml-monitoring-console) | Browser-based transaction monitoring console: typology rules, explainable alerts, STR narrative drafts. [Live demo](https://herui03.github.io/aml-monitoring-console/) | JavaScript, synthetic data |
| [sme-risk-survey-panel](https://github.com/herui03/sme-risk-survey-panel) | Nine waves of an SME insurance survey harmonised into one panel. The same variable carried three different codeframes across the decade and the same code meant two different things; the harmonisation is the deliverable. Ships with a synthetic-data generator so the pipeline runs end to end | R, ggplot2, logistic and count models |

### AI agents and automation

| Project | What it is | Stack |
|---|---|---|
| [ad-ops-multi-agent](https://github.com/herui03/ad-ops-multi-agent) | Portfolio prototype for a simulated advertising operations use case: an orchestrator routes to six specialist agents, with retrieval-grounded compliance checks and a human-review interface. This is a demonstration, not a production deployment or client engagement | Python, LangGraph, FastAPI, React, Groq |
| [pdf2audiobook](https://github.com/herui03/pdf2audiobook) | Small tool that turns a PDF into an audiobook with free neural voices, with chapter splitting, a CLI and a web UI | Python, Edge TTS, Gradio |

An analytics-engineering project (dbt and DuckDB warehouse with 170 tests, lead scoring, and a causal-inference study on a 14M-row advertising RCT) is kept private for now; happy to walk through it.

Each analysis repo keeps a `docs/` folder of things that went wrong, how they were caught, and what the fix cost. Those are usually the most useful part.

## What I work with

- Querying and data work: SQL (Postgres, MySQL, DuckDB), Python (pandas), R (dplyr, tidyr), Excel (Power Query, PivotTables)
- Modelling: regression, tree ensembles, model comparison and explainability (SHAP), calibration, A/B and causal analysis
- Pipelines and BI: dbt, DuckDB, Tableau, Power BI (working knowledge)
- LLM applications: LangGraph and LangChain agent workflows, RAG, prompt design with structured outputs, human-in-the-loop review
- Domain: treasury operations and reconciliation, retail banking pricing, AML and KYC, credit portfolio monitoring, insurance survey research

## Contact

[LinkedIn](https://www.linkedin.com/in/heruidou), Singapore
